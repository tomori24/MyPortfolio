<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome Vue.js App"/> -->
    <h1>Portfolio</h1>
    <About />
    <Work />
    <Experience />
    <Contact />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import About from './components/About.vue'
import Experience from './components/Experience.vue'
import Work from './components/Work.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    About,
    Experience,
    Work,
    Contact
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #242424;
  background-color: #ffffff;
}
h1, h2{
  color: cornflowerblue;
}
</style>
