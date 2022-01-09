<template>
  <div id="app">
    <myView></myView>
  </div>
</template>

<script>
import myView from './views/myView.vue'

export default {
  name: 'app',
  components: {
    myView
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
