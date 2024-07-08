<template>
  <div id="app">
    <Navbar />
    <div class="main-content">
      <!-- <Sidebar /> -->
      <router-view></router-view>
    </div>
  </div>
</template>

<script setup lang="ts">
import Navbar from '@/components/Navbar.vue'
</script>

<style lang="scss">
 // Adjust styles as needed
</style>