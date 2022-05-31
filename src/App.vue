<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <h3>666</h3>
    <h2>222</h2>
    <h2>111</h2>
    <Left></Left>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Left from '@/components/Left.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    Left,
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
