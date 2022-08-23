<template>
  <div id="app">
    <MyTitle/>
    <Hero/>
  </div>
</template>

<script>
import MyTitle from './components/myTitle.vue';
import Hero from './components/hero.vue';

export default {
  name: 'App',
  components: {
    MyTitle,
    Hero
}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  margin-top: 60px;
  overflow-x: hidden;
}
</style>
