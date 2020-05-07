<template>
  <div id="app">
    <Conversor moeda-a="USD" moeda-b="BRL"/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Conversor from "./components/Conversor.vue"
export default {
  name: 'App',
  components: {
    Conversor
  }
}
</script>

<style>
#background{
  background-color: slategrey;
}
#app {
    display: flex;
    align-items: center;
    justify-content: center;
  margin: auto;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  
}
</style>
