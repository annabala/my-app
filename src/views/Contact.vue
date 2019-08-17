<template>
  <div class="contact">
    <h1 class="contact-h1">Contact me</h1>
    <form class="contact-form">
      <div class="contact-form-group">
        <label for="name">Name</label>
        <input type="text" name="input">
      </div>
      <div class="contact-form-group">
        <label for="">Last name</label>
        <input type="text" name="input">
      </div>
      <div class="contact-form-group">
        <label for="">E-mail</label>
        <input type="email" name="input">
      </div>
      <div class="contact-form-group">
        <label for="">Phone number</label>
        <input type="tel" name="input">
      </div>
      <div class="contact-form-group">
        <button type="submit">Send</button>
      </div>  
    <div class="contact-form__decor contact-form__decor--light-blue"></div>
    <div class="contact-form__decor contact-form__decor--dark-blue"></div>
    </form>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'contact'
};
</script>

<style lang="scss" scoped>
@import "../styles/views/contact.scss";
</style>
