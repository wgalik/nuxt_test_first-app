<script setup lang="ts">
useHead({
  title: "Home",
});

const { data } = useFetch("/api/userdetails");
</script>
<template>
  <h1>Hello world</h1>
  <!-- <a href="/about">Goto About page</a> -->
  <p>{{ data.msg }}</p>
  <NuxtLink to="/about">Goto About page</NuxtLink>
</template>
