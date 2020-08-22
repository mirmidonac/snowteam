<template>
  <div id="app">
    <Header/>
    <Carousel/>
    <Cards/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Carousel from './components/Carousel.vue'
import Cards from './components/Cards.vue'

export default {
  name: 'App',
  components: {
    Header,
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
  background-color: #2c3e50;
}
</style>
