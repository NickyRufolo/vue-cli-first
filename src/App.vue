<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <appTitle /> 
    <!-- // in questo punto del codice di App Vue stampami il componente-->
  </div>
</template>

<script>
// ma per far si che funzioni devo importarmelo in import
import appTitle from './components/appTitle.vue'

export default {
  name: 'App',
  components: {
    appTitle
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
