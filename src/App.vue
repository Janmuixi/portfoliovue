<script setup lang="ts">
import HeaderMain from './components/HeaderMain.vue';
import AboutMe from './components/AboutMe.vue'
</script>

<template>
  <div class="flex items-center flex-col">
    <div class="max-w-[1500px] px-6">
      <HeaderMain />

      <main class="md:pb-[60px] py-4">
        <AboutMe />
      </main>
    </div>
  </div>
</template>
