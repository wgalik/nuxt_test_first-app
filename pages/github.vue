<script setup>
const { data: users } = useFetch("https://api.github.com/users");
</script>

<template>
  <h1>GitHub Users</h1>
  <div v-for="user in users">
    <h2>{{ user.login }}</h2>
    <p>name: {{ user?.name }}</p>
    <p>id is {{ user.id }}</p>
  </div>
</template>
