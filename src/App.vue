<template>
  <div id="app">
    <Skillset />
  </div>
</template>

<script>
import Skillset from './components/Skillset.vue'

export default {
  name: 'App',
  components: {
    Skillset
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
