<template>
  <div class="wrapper">
    <h1 class="h1">Contact me</h1>
    <div class="form">
      <div class="form-group">
        <label for="name">Name</label>
        <input type="text" name="input" value="Type here">
      </div>
      <div class="form-group">
        <label for="">Last name</label>
        <input type="text" name="input" value="Type here">
      </div>
      <div class="form-group">
        <label for="">E-mail</label>
        <input type="email" name="input" value="Type here">
      </div>
      <div class="form-group">
        <label for="">Phone number</label>
        <input type="tel" name="input" value="Type here">
      </div>
      <div class="form-group">
        <button type="submit">Send</button>
      </div>  
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
.wrapper {
  max-width: 500px;
  .form {
    display: flex;
    flex-direction: column;
    .form-group {
      display: flex;
      flex-direction: column;
    }
  }
}
</style>