<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Carousel/>
    <Cards/>
  </div>
</template>

<script>
import Carousel from './components/Carousel.vue'
import Cards from './components/Cards.vue'

export default {
  name: 'App',
  components: {
    Carousel,
    Cards
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
