<script setup lang='ts'>
import Navbar from './components/personal/navbar/Navbar.vue';
import Footer from './components/personal/footer/Footer.vue';
import Timer from './components/personal/timer/Timer.vue';
</script>

<template>
  <div class="h-screen flex flex-col justify-between dark:bg-gray-900">
    <Navbar />

    <div class="flex flex-1 bg-gray-900">
      <div class="flex flex-1 flex-col justify-center items-center">
        <p class="text-white text-start">asjdfasnfk</p>
        <Timer />
      </div>
    </div>

    <Footer />
  </div>
</template>