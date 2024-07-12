<script setup lang='ts'>
import Navbar from './components/personal/navbar/Navbar.vue';
import Footer from './components/personal/footer/Footer.vue';

</script>

<template>
  <div class="h-screen flex flex-col justify-between dark:bg-gray-900">
    <Navbar />

    <div class="flex flex-1 flex-col justify-center items-center bg-gray-900">
      <div class="">
          <div class="flex flex-col items-center space-y-4 bg-gray-800 p-6 rounded">
            <div class="flex space-x-4">
              <button class="px-4 py-2 bg-blue-500 text-white rounded">Focus</button>
              <button class="px-4 py-2 bg-green-500 text-white rounded">Break</button>
            </div>
            <div class="text-9xl font-bold text-white">00:00:00</div>
            <button class="px-4 py-2 bg-red-500 text-white rounded">Start</button>
          </div>
      </div>
    </div>

    <Footer />
  </div>
</template>