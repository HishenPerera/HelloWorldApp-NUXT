<script setup lang="ts"></script>

<template>
  <Header />
  <div
    class="flex flex-col items-center justify-center min-h-screen bg-[#176e43]"
  >
    <h1 class="text-4xl font-bold text-[#bfffde]">Hello Hishen</h1>
    <div class="flex">
      <h1
        class="text-4xl font-bold text-[#bfffde] drop-shadow-md"
        style="margin-right: 10px"
      >
        Welcome to
      </h1>
      <h1 class="text-4xl font-bold text-[#18ff88] drop-shadow-md">
        NUXT Framework
      </h1>
    </div>
  </div>
  <Footer />
</template>

<style scoped>
.flex,h1 {
  font-family: "Poppins";
}
</style>
