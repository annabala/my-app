<template>
  <div class="home">
    <div class="container">
      <h1 class="h1">Front end Developer</h1>
      <div class="shapeContainer">
        <div class="shapeContainer__block">
            <div class="shapeContainer__block__item"><p></p></div>
            <div class="shapeContainer__block__item"><p>jQuery</p></div>
            <div class="shapeContainer__block__item"><p>sass</p></div>
            <div class="shapeContainer__block__item"><p>html</p></div>
        </div>
        <div class="shapeContainer__block">
          <div class="shapeContainer__block__item"><p>vue.js</p></div>
          <div class="shapeContainer__block__item"><p></p></div>
          <div class="shapeContainer__block__item"><p>webpack</p></div>
          <div class="shapeContainer__block__item"><p>git</p></div>
        </div>
        <div class="shapeContainer__block">
          <div class="shapeContainer__block__item"><p>materialize</p></div>
          <div class="shapeContainer__block__item"><p>bootstrap</p></div>
          <div class="shapeContainer__block__item"><p>angular</p></div>
          <div class="shapeContainer__block__item"><p>javascript</p></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'home',
};
</script>
<style lang="scss" scoped>
@import "../styles/views/home.scss";
</style>
