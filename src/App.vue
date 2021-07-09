<template>
  <div id="app">
    <img class="bg" src="./assets/background.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
  background-image: "assets/background.png";
  color: white;
}

.bg {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  z-index: -1;
}
</style>
