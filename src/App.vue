<template>
  <div id="app" class="flex h-screen justify-center items-center">
    <img class="w-32 h-32 rounded-full" src="@/assets/avatar.svg">
    <div>
      <h2 class="text-lg text-center">t-tajiri</h2>
      <Skillset />
    </div>
  </div>
</template>

<script>
import Skillset from '@/components/Skillset.vue'

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
}
</style>
