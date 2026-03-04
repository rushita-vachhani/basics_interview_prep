<script setup>
import { ref } from "vue";
const name = ref("Rushita");
const year = ref("2026");
</script>

<template>
  <h1>Hello {{ name }}</h1>
  <footer>
    &copy;
    <p>{{ year }}</p>
  </footer>
</template>

<style scoped>
footer p {
  color: red;
}
</style>
