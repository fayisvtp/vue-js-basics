<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Home userName="fayis" data="front end developer" msg="in bridgeon solution" />
  <Home userName="alli" data="front end developer" msg="in bridgeon solution" />
  <Home userName="abid" data="front end developer" msg="in bridgeon solution" />
  <Home userName="shamil mon" data="BDE" msg="in bridgeon solution" />

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'
export default {
  name: 'App',
  components: {
    // HelloWorld,
    Home  
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
