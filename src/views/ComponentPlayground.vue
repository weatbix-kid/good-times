<template>
  <div class="about">
    <h1>This is a test page</h1>
  </div>
  <TestComponent />
  <FlyoutMenu />
  <Calendar />
</template>

<script setup lang="ts">
import TestComponent from '../components/TestComponent.vue';
import FlyoutMenu from '../components/FlyoutMenu.vue';
import Calendar from '../components/Calendar.vue'
</script>