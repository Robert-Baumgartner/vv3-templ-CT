<template>
  <div>
    <p class="text-center text-xl ">{{ name }} sagt: Hallo!</p>
  </div>
</template>

<script setup>
defineProps({
  name: String,
});
</script>