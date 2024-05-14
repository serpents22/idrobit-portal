<script setup>
import { ref } from 'vue'

</script>
<template>
  <div
    class="bg-[#353535] xl:bg-[url('@/assets/login-bg.png')] w-full xl:h-full bg-cover absolute z-0 flex flex-col gap-4 lg:gap-20 p-[20px]">
    <div class="mx-auto text-white pt-10 lg:pt-20">
      <h1 class="text-2xl">Benvenuti nei</h1>
      <h1 class="text-[40px] font-semibold">Portali di Idrobit</h1>
    </div>
    <div class="grid grid-cols-1 sm:grid-cols-2 items-center mx-auto gap-4 lg:gap-10">
      <div class="card">
        <a href="https://idrolife.portale-idrobit.com" target="_blank">
          <img src="../assets/idrolife-icon.png" alt="">
        </a>
      </div>
      <div class="card">
        <a href="https://idrores.portale-idrobit.com" target="_blank">
          <img src="../assets/idrores-icon.png" alt="">
        </a>
      </div>
      <div class="card">
        <a href="https://idropro.portale-idrobit.com" target="_blank">
          <img src="../assets/idropro-icon.png" alt="">
        </a>
      </div>
      <div class="card">
        <a href="https://idroserre.portale-idrobit.com" target="_blank">
          <img src="../assets/idroserre-icon.png" alt="">
        </a>
      </div>
    </div>
    <div class="flex items-center justify-center mb-2 mx-auto text-white">
      <div class="flex gap-4 justify-center items-center">
        <h2 class="text-[8px] sm:text-base">Design By</h2>
        <div class="flex gap-2 items-center">
          <img class="w-6" src="../assets/101logo.png" alt="" srcset="">
          <h2 class="text-[8px] sm:text-base font-semibold">101 Team</h2>
        </div>
      </div>
    </div>
  </div>

</template>

<style scoped>
p {
  @apply select-none
}

.card {
  @apply bg-gradient-to-t from-[#353535]/10 via-white to-white rounded-lg shadow-lg items-center justify-center flex p-6 w-60 hover:scale-105 transition-transform duration-200 h-36
}
</style>
