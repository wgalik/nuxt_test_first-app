<script setup lang="ts">
const route = useRoute();
</script>
<template>
  <h2>User page {{ route.params.id }}</h2>
</template>
