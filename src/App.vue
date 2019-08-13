<template>
  <div id="app">
    <HelloWorld msg="Search here"/>
    <MapView/> 
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MapView from './components/MapView.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    MapView
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
</style>
