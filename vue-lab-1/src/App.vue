<template>
  <div id="app">
    <MyComponent />
  </div>
</template>

<script>

import MyComponent from './components/MyComponent.vue'

export default {
  name: 'app',
  components: {
    MyComponent
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:black;
  margin-top: 60px;
}
</style>
