<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Home userName="fayis" data="front end developer" msg="in bridgeon solution" />
 <Interpulation/>
 <methods/>
 <Events/>
 <CountAppevents/>
 <twoway-binding/>
<inputvalue/>
</template>

<script>
import Events from './components/Events.vue'
// import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'
import Interpulation from './components/Interpulation.vue'
import Methods from './components/Methods.vue'
import CountAppevents from './components/CountAppevents.vue'
import TwowayBinding from './components/TwowayBinding.vue'
import Inputvalue from './components/InputVlue.vue'


export default {
  name: 'App',
  components: {
    // HelloWorld,
    Home,
    Interpulation,
    Methods,
    Events  ,
    CountAppevents,
    TwowayBinding,
    Inputvalue,


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
