<template>
  <div id="app">
    <layout></layout>
  </div>
</template>

<script>
import layout from './view/layout/index.vue'

export default {
  name: 'app',
  components: {
      layout
  }
}
</script>

<style>
  body{
    margin:0;
  }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /*color: #fff;*/
  /*background: #002762;*/
}
</style>
