<script setup>
import Footer from './components/Footer.vue';
import Navbar from './components/NavbarComponent.vue'
</script>

<template>
  <div class="min-h-screen flex flex-col bg-gray-100">
    <Navbar />
    <div class="flex-1 container mx-auto px-4 py-6">
      <router-view></router-view>
    </div>
    <Footer />
  </div>
</template>