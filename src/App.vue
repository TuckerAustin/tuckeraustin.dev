<template>
  <header>
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link :to="{ name: 'About' }">About</router-link>
      <router-link :to="{ name: 'Contact' }">Contact</router-link>
      <router-link to="/projects">Projects</router-link>
      <router-link :to="{ name: 'Resume' }">Resume</router-link>
    </div>
  </header>
  <div id="content">
    <router-view />
  </div>
</template>

<style>
html,
body {
  height: 100%;
  margin: 0;
  padding: 0;
  background: linear-gradient(
    45deg,
    rgb(26, 26, 26) 11%,
    rgb(0, 156, 0) 74%,
    rgb(26, 26, 26) 15%
  );
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #ffffff;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #06940d;
  text-decoration: none;
  padding: 10px;
  border-radius: 4px;
}

#nav a:hover {
  color: snow;
}

header {
  display: grid;
  justify-content: right;
  padding: var(--sl-spacing-small);
}

#content {
  display: flex;
  align-items: center;
  flex-direction: column;
}

#content > * {
  max-width: 1200px;
  padding: 0 16px;
}
</style>
