<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <DEMO></DEMO>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import DEMO from './index/demo.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,DEMO
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
