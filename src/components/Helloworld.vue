<script setup lang="ts">
defineProps<{ msg: string }>()
</script>

<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Welcome to your Vue 3 + TypeScript app 🚀</p>
  </div>
</template>

<style scoped>
h1 {
  color: #42b983;


}


</style>
