<template>
  <div
    id="app"
    class="flex h-screen flex-col md:flex-row justify-center items-center"
  >
    <img
      class="mx-auto md:mx-0 w-40 h-40 rounded-full"
      src="@/assets/avatar.svg"
      alt="avatar"
    >
    <div>
      <h2 class="mt-3 md:mt-0 text-xl text-center">
        t-tajiri
      </h2>
      <div class="mt-1 text-center text-lg text-teal-600">
        Web Developer
      </div>
      <Skillset />
      <Footer />
    </div>
  </div>
</template>

<script>
import Skillset from '@/components/Skillset.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'App',
  components: {
    Skillset,
    Footer
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
