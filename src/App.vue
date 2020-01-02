<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <h1>Vuex</h1>
    <app-result/>
    <app-counter/>
    
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import AppResult from "./components/Result";
import AppCounter from "./components/Counter";

export default {
  name: "app",
  components: {
    AppResult,
    AppCounter
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
