<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <h1 class="green">{{ msg }}</h1>
  <h3>
    You are on the hompage
  </h3>
</template>

<style scoped>

</style>
