<script setup lang="ts">
definePageMeta({
  layout: "admin",
});

useHead({
  title: "About",
  meta: [{ name: "description", content: "This page is about nuxt" }],
});
</script>

<template>
  <h1>About</h1>

  <NuxtLink to="/">Go back</NuxtLink>
</template>
