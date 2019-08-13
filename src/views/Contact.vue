<template>
  <div class="contact">
    <h1 class="contact-h1">Contact me</h1>
    <div class="contact-form">
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
    </div>
  </div>
</template>



<script>
// @ is an alias to /src
export default {
  name: 'contact',
};
</script>
<style lang="scss" scoped>
.contact {
  &-h1 {
    color: #FE4A49;
  }
  &-form {
    max-width: 500px;
    margin: 3rem auto;
    display: flex;
    flex-direction: column;
    &__decor {
      display: inline-block;
      width: 120px;
      height: 120px;
      position: absolute;
      transform: rotate(45deg);
      z-index: -1;
      &--light-blue {
        background-color: #4AD7D1;
        top: 0;
        right: -100px;
      }
      &--dark-blue {
        background-color: #001730;
        bottom: 0;
        left: -100px;
      }
    }
  }
  &-form-group {
    display: flex;
    flex-direction: column;
    & label {
      margin: 0 0 5px 0;
      transition: font-size .4s ease;
    }
    & input {
      font-size: 1rem;
      font-family: "Muli";
      border: none;
      border-bottom: 2px solid #001730;
      margin: 0 0 15px 0;
      padding: 10px 0;
      transition: border-bottom .4s ease;
      &:last-of-type {
        margin: 0 0 30px 0;
      }
      &:focus {
        outline: none;
        border: none;
        border-bottom: 2px solid #4AD7D1;
      }
    }
    & button {
      border: none;
      background-color: #4AD7D1;
      color: #001730;
      font-weight: 600;
      padding: 10px 0;
      font-size: 1rem;
    }
  }
}
</style>