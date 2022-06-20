<template>
  <div id="app">
    <PageTitle></PageTitle>
    <PageHero></PageHero>
  </div>
</template>

<script>
import PageTitle from './components/PageTitle.vue'
import PageHero from './components/PageHero.vue'


export default {
  name: 'App',
  components: {
    PageTitle,
    PageHero,
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
