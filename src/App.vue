<template>
  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/playground">Playground</RouterLink>
  </nav>
  <RouterView />
</template>

<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>
