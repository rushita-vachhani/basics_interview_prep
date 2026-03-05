<script setup>
import { ref } from "vue";
const name = ref("Rushita");
</script>

<template>
  <header>
    <h1>Hello {{ name }}</h1>
  </header>
</template>

<style scoped>
header h1 {
  color: blue;
}
</style>
