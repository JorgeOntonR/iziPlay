<template>
  <div id="app">
      <img id = "logo" src="./assets/sharingan.png">
    <Home/>
    <br/>
  </div>
</template>

<script>
import Home from './components/Home'
//import Contar from './components/Contar'
import Vue from 'vue'
import BootstrapVue from 'bootstrap-vue'
//import './App.css';

Vue.use(BootstrapVue)

import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

export default {
  name: 'App',
  components: {
    Home
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

@media (prefers-reduced-motion: no-preference) {
  #logo {
    height: 750px;
    animation: App-logo-spin infinite 5s linear;
  }
}

@keyframes App-logo-spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}
</style>
