<template>
  <div class="flex flex-col min-h-screen bg-primary">
    <Navigation />
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from 'vue-router';
import Navigation from './components/Navigation.vue';
import './Tailwind.css';

</script>

<style lang="scss" scoped>

</style>