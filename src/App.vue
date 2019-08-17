<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/Projects">Projects</router-link> |
      <router-link to="/Contact">Contact</router-link>
    </div>
    <router-view/>
  </div>
</template>
<script>

</script>
<style lang="scss">
@import "./styles/basics/base.scss";
</style>
