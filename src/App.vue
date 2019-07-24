<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Header msg="Welcome to Your Vue.js App"/>
    <packagebutton/>
    <platform/>

  </div>
</template>

<script>
import Header from './components/Header.vue'
import packagebutton from './components/packagebutton.vue'
import platform from './components/platform.vue'

export default {
  name: 'app',
  components: {
    Header,
    packagebutton,
    platform
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

}
</style>
