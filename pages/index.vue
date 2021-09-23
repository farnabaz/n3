<template>
  <div>
    <h1>INDEX</h1>
    <div>
      <NuxtLink to="/">INDEX</NuxtLink>
      |
      <NuxtLink to="/about">ABOUT</NuxtLink>
    </div>
  </div>
</template>

<script nuxt setup lang="ts">
useMeta({
  title: "INDEX"
})
</script>