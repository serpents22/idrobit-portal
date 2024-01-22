<script setup>
import { ref } from 'vue'

</script>
<template>
  <div class="bg-[#353535] xl:bg-[url('@/assets/login-bg.png')] w-full h-full bg-cover absolute z-0 flex flex-col gap-4 lg:gap-20 p-[20px]">
    <div class="mx-auto text-white pt-10 lg:pt-20">
      <h1 class="text-2xl">Benvenuti nei</h1>
      <h1 class="text-[40px] font-semibold">Portali di Idrobit</h1>
    </div>
    <div class="flex flex-col items-center mx-auto gap-4 lg:gap-10">
      <div class="flex flex-col lg:flex-row gap-4 lg:gap-10">
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
      </div>
      <div class="card">
        <a href="https://idropro.portale-idrobit.com" target="_blank">
          <img src="../assets/idropro-icon.png" alt="">
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>
p {
  @apply select-none
}

.card {
  @apply bg-white rounded-lg shadow-lg items-center justify-center flex p-6 w-60 hover:scale-105 transition-transform duration-200
}
</style>
