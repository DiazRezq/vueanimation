<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="container">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </header>
  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
  padding: 3px;
}


.nav-link:last-child {
  margin-right: 0;
}

.container {
  max-width: 300px;
  margin: auto;
  padding: 20px;
}
</style>
