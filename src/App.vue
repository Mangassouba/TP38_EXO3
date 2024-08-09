<template>
  <div id="app">
    <Navbar />
    <jumbotronComponents />
    <CTAComponents />
    <cardsComponents />
    <footerComponents />
  </div>
</template>

<script>
import Navbar from './components/NavbarComponents.vue'
import jumbotronComponents from './components/jumbotronComponents.vue'
import CTAComponents from './components/CTAComponents.vue'
import cardsComponents from './components/cardsComponents.vue'
import footerComponents from './components/footerComponents.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    jumbotronComponents,
    CTAComponents,
    cardsComponents,
    footerComponents
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
}
</style>
