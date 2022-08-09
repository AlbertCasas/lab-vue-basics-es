<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <NavBarFooter/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavBarFooter from './components/NavBarFooter.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    NavBarFooter
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
