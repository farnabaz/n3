<template>
  <div>
    <h1>ABOUT</h1>
    <div>
      <NuxtLink to="/">INDEX</NuxtLink>
      |
      <NuxtLink to="/about">ABOUT</NuxtLink>
    </div>
  </div>
</template>

<script nuxt setup lang="ts">
useMeta({
  bodyAttrs: {
    a: "a"
  }
})
</script>