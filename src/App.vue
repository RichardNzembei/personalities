<script setup>
import AboutCard from './components/AboutCard.vue';
import AdminCard from './components/AdminCard.vue';
</script>

<template>
  <header class="flex flex-col justify-center items-center lg:flex-row lg:justify-between lg:items-start lg:pr-8">
    <div class="wrapper flex flex-col items-center lg:flex-row">
      <nav class="text-center text-sm mt-8 lg:text-left lg:mt-2 lg:text-base">
        <a href="#" class="inline-block px-4 py-2 lg:py-4 border-l-0 lg:border-l border-gray-300 text-gray-700 hover:text-black focus:ring-2 focus:ring-blue-500">Chats</a>
        <a href="#" class="inline-block px-4 py-2 lg:py-4 border-l border-gray-300 text-gray-700 hover:text-black">Updates</a>
        <a href="#" class="inline-block px-4 py-2 lg:py-4 border-l border-gray-300 text-gray-700 hover:text-black">Groups</a>
        <a href="#" class="inline-block px-4 py-2 lg:py-4 border-l border-gray-300 text-gray-700 hover:text-black">Settings</a>
      </nav>
    </div>
  </header>

<AdminCard/>
<AboutCard/>

</template>

