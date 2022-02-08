<template>
  <div class="flex flex-col justify-center items-center">
    <p class="text-5xl mt-4">
      <span class="text-red-500"><i class="far fa-heart"></i></span>
      {{ msg }}
      <span class="text-red-500"><i class="far fa-heart"></i></span>
    </p>
    <img class="w-40 mt-4" src="@/assets/logo.svg" alt="Vue logo" />
  </div>
  <SayHello name="Robert" class="mt-2 italic"></SayHello>
</template>

<script setup>
import SayHello from '@/components/SayHello.vue';

const msg = 'Willkommen!';
</script>

<style>
</style>
