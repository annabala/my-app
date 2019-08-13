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

<style lang="scss">
@font-face {
  font-family: "Muli";
  src: url("assets/fonts/Muli-Regular.ttf") format("ttf");
}
body {
  font-family: "Muli";
}
</style>
