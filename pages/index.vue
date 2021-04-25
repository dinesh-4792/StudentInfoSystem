<template>
  <div class="w-screen h-screen bg-blue-500">
    <div class="w-full">
      <main-header>
      </main-header>
    </div>
    <div class="w-full flex">
      <div class=" w-1/2 flex justify-end">
        <div class=" flex flex-col p-16 m-20 bg-white rounded-2xl">
          <h2 class="text-lg font-bold text-blue-700 pb-4">Admin Login</h2>
          <button class="py-2 px-4 bg-yellow-500 rounded-xl text-white shadow-lg"><NuxtLink to="/administrator">GO TO LOGIN PAGE</NuxtLink></button>
        </div>
      </div>
      <div class=" w-1/2 flex justify-start">
        <div class="flex flex-col p-16 m-20 bg-white rounded-2xl">
          <h2 class="text-lg font-bold text-blue-700 pb-4">Student Login</h2>
          <button class="py-2 px-4 bg-yellow-500 rounded-xl text-white shadow-lg"><NuxtLink to="/student">GO TO LOGIN PAGE</NuxtLink></button>
        </div>
      </div>
  </div>
  </div>
</template>

<script>
import MainHeader from '../components/mainHeader.vue'
export default {}
</script>

<style>

</style>

MainHeader