<template>
  <div id="app">
    <div @click="test()">bbbb</div>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
var moment = require('moment');
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data: function() {
    return: {
      moment: moment,
    }
  },
  methid: {
    test: function(){
      console.log('ssss');
    }
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
