<template>
  <div id="app">
    <TitlePro />
    <HeroJumbo />
  </div>
</template>

<script>
import TitlePro from './components/TitlePro.vue'
import HeroJumbo from './components/HeroJumbo.vue'
export default {
  name: 'App',
  components: {
    TitlePro,
    HeroJumbo
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
