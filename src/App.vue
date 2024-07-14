<script setup lang='ts'>
import Navbar from './components/personal/navbar/Navbar.vue'
import Footer from './components/personal/footer/Footer.vue'
import Timer from './components/personal/timer/Timer.vue'
import Historic from './components/personal/historic/Historic.vue'
</script>

<template>
  <div class="h-screen flex flex-1 flex-col justify-between">
    <Navbar />

    <div class="flex flex-1 bg-gray-900">
      <div class="flex flex-1 justify-center items-center">

        <div id="historico" class="flex gap-6">
          <Timer />
          <Historic />
        </div>

      </div>
    </div>

    <Footer />
  </div>
</template>

<style>
@media screen and (max-width: 640px) {
  #historico {
    flex-direction: column;
  }
}
</style>