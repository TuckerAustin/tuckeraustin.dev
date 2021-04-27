<template>
  <div class="header">
    <div class="name">
      <h1>Tucker Austin</h1>
      <h4 class="title">Front-end Web Developer</h4>
    </div>
    <div class="info">
      <p>Snohomish, Washington</p>
      <p>(206) 856-8526</p>
      <p>tucker.austin@gmail.com</p>
      <p>github.com/TuckerAustin</p>
    </div>
  </div>
  <div class="body">
    <p>
      SUMMARY: Highly motivated Front-end Web Developer with experience in
      React, Vue and LitElement with a foundation in HTML, CSS and JavaScript
    </p>
    <p>
      ACCOMPLISHMENTS: Created websites, custom blog platforms, reaction timer,
      and project planner using React and Vue 3
    </p>
    <p>EXPERIENCE Financial Planning Application</p>
    <p>Freelance Web Developer March 2021-April 2021</p>
    <p>
      Collaborated with a lead developer to build single page app using web
      components with LitElement Wired components together using Shoelace UI Web
      Component Library Worked with MobX state manager to store and manipulate
      application state Setup SPA router for handling page navigation and signin
      flow
    </p>
    <p>Aviation Technical Services Everett WA</p>
    <p>Apprentice Mechanic III July 2017 - June 2020</p>
    <p>
      Repaired, modified, and replaced aircraft parts in a safe and timely
      manner Accurately completed required maintenance-related paperwork
      Communicated effectively with other maintenance personnel by keeping
      co-workers and leadership apprised of work progress and difficulties as
      they arose
    </p>
    <p>
      EDUCATION Lake Washington Institute of Technology - Electronics Technician
      2006 - 2009
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style>
.header {
  display: flex;
  width: calc(100% - 32px);
  justify-content: space-between;
}
.name {
  text-align: center;
}

.info {
  text-align: right;
  justify-content: right;
}

.info p {
  margin: 6px;
}

h1 {
  line-height: 1;
  padding: 8px;
  margin: 0;
}

h4.title {
  color: #06940d;
  line-height: 1;
  padding: 0;
  margin: 0;
}
.body {
  display: grid;
  float: left;
  text-align: left;
  margin: 50px 0;
}
</style>