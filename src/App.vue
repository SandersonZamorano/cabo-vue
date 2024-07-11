<script setup lang='ts'>
import Button from './components/ui/button/Button.vue'

const test = () => {
  document.body.classList.toggle('red')
}
</script>

<template>
  <div class="h-screen dark:bg-gray-900">
    <Button @click="test()"> 
      Toggle Dark Mode
    </Button>
  </div>
</template>