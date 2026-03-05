<script setup>
import { ref } from "vue";
const year = ref("2026");
</script>

<template>
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
