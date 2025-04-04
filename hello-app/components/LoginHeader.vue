<script setup lang="ts"></script>

<template>
  <header class="bg-[#1c8750] shadow">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between h-16">
        <div class="flex">
          <NuxtLink to="/" class="flex items-center text-xl font-bold text-[#ceffe5]">
            Login Header
          </NuxtLink>
        </div>
        <div class="flex items-center space-x-4">
          <NuxtLink to="/" class="text-[#bfffde] hover:text-[#a8ffd2] font-bold">Home</NuxtLink>
          <NuxtLink to="/about" class="text-[#bfffde] hover:text-[#a8ffd2] font-bold ">About</NuxtLink>
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>
.flex, h1{
    font-family: 'Poppins';
}
</style>