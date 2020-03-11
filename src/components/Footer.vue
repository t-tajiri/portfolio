<template>
  <div class="flex justify-center mt-3">
    <a
      href="#twitter"
      class="mx-8 text-xl"
    >
      <font-awesome-icon :icon="['fab', 'twitter']" />
    </a>
    <a
      href="#github"
      class="mx-8 text-xl"
    >
      <font-awesome-icon :icon="['fab', 'github']" />
    </a>
    <a
      href="#blog"
      class="mx-8 text-xl"
    >
      <font-awesome-icon :icon="['fas', 'blog']" />
    </a>
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>