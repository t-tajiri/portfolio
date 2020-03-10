<template>
  <div
    id="app"
    class="flex h-screen flex-col md:flex-row justify-center items-center"
  >
    <img
      class="mx-auto md:mx-0 w-32 h-32 rounded-full"
      src="@/assets/avatar.svg"
      alt="avatar"
    >
    <div>
      <h2 class="text-xl text-center">
        t-tajiri
      </h2>
      <div class="mt-1 text-center text-lg text-teal-600">
        Web Developer
      </div>
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
