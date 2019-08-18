<template>
  <div id="app">
    <div class="container">
      <div id="nav" class="navList">
        <router-link to="/" class="navList__item navList__item-active">Home</router-link>
        <router-link to="/Projects" class="navList__item">Projects</router-link>
        <router-link to="/Contact" class="navList__item">Contact</router-link>
      </div>
      <router-view/>
    </div>
  </div>
</template>
<script>

</script>
<style lang="scss">
@import "./styles/basics/base.scss";
</style>
