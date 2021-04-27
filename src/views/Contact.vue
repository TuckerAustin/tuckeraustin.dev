<template>
  <div class="contact">
    <h1>Contact Me</h1>
  </div>
  <sl-form
    class="form-overview"
    name="contact"
    method="POST"
    data-netlify="true"
  >
    <sl-input name="name" label="Name" required>Name</sl-input>
    <sl-input name="email" label="Email" required>Email</sl-input>
    <sl-textarea name="message" label="Message" required>Message</sl-textarea>
    <sl-button type="success" submit>Submit</sl-button>
  </sl-form>
</template>

<script>
export default {
  data() {
    return {
      name: "",
      email: "",
      message: "",
    };
  },
};
</script>

<style>
sl-form {
  max-width: 420px;
  margin: 30px auto;
  background: white;
  text-align: left;
  padding: 40px;
  border-radius: 10px;
}
sl-label {
  color: #aaa;
  display: inline-block;
  margin: 25px 0 15px;
  font-size: 0.6em;
  text-transform: uppercase;
  letter-spacing: 1px;
  font-weight: bold;
}
sl-button {
  display: grid;
  justify-content: right;
  padding: 4px 0;
}
</style>