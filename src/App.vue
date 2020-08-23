<template>
  <div id="app">
    <Header/>
    <Carousel/>
     <AboutUs/>
    <Cards/>
    <Membership/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Carousel from './components/Carousel.vue'
import Cards from './components/Cards.vue'
import AboutUs from './components/AboutUs.vue'
import Membership from './components/Membership.vue'

export default {
  name: 'App',
  components: {
    Header,
    Carousel,
    AboutUs,
    Cards,
    Membership
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
