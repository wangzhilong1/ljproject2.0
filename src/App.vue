<template>
  <div id="app">
    <layout></layout>
  </div>
</template>

<script>
import layout from '@/Apps/layout'
export default {
  name: 'app',
  components:{layout}
}
</script>

<style lang="scss">
html, body, #cesiumContainer {
          width: 100%; height: 100%; margin: 0; padding: 0; overflow: hidden;
 }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  width: 100%;
  height: 100%;
  position: absolute;
}
</style>
