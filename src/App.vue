<template>
  <div id="app">
    <GoogleMap></GoogleMap>
    <PicturePoints></PicturePoints>

  </div>
</template>

<script>
import PicturePoints from './components/PicturePoints.vue'
import GoogleMap from './components/GoogleMap.vue'

export default {
  name: 'app',
  components: {
    PicturePoints,
    GoogleMap,
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
