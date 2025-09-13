<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <header>
    <img src="../public/bscs-1a-logo-text.png" alt="BSCS-1A Logo" />
    <p class="bold">BSCS-1A</p>
  </header>

  <main>
    <RouterView />
  </main>
</template>

<style scoped>
header {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

img {
  height: 20rem;
  margin-bottom: -1.5rem;
}
</style>
