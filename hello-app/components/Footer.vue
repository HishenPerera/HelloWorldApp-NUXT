<template>
  <footer class="bg-white shadow">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4">
      <div class="flex justify-between items-center">
        <p class="text-gray-600">© 2023 Hello World App. All rights reserved.</p>
        <div class="flex space-x-4">
          <NuxtLink to="/" class="text-gray-600 hover:text-blue-600">Home</NuxtLink>
          <NuxtLink to="/about" class="text-gray-600 hover:text-blue-600">About</NuxtLink>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts"></script>

<style scoped>
.flex, h1{
    font-family: 'Poppins';
}
</style>