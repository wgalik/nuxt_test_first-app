<script setup>
const { data: user } = useFetch("https://api.github.com/users/wgalik");
</script>

<template>
  <h1>name: {{ user?.name }}</h1>
</template>
