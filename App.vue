<template>
  <div id="app">
    <h1 :class="'notActive'">{{name}}</h1>
    <h1 :class="'active'">{{name}}</h1>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="hello world"/>
  </div>
</template>

<script>
import HelloWorld from './components/kalkulator.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
