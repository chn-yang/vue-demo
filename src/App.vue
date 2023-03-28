<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HiComponent name="vue" />
  <router-view/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HiComponent from './components/Hi.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    HiComponent
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
