<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <header style="text-align: center; margin-top: 20px">
    <img src="/honda-civic-si-3.jpg" alt="Honda Civic Si" width="200" />

    <h1 style="color: mediumseagreen">¡Lo hiciste!</h1>
    <p>Welcome to your Vue 3 + TypeScript app</p>

    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
  </header>
</template>
