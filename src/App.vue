<template>
  <div class="bg-red-900 text-green-200">{{ msg }}</div>
</template>

<script setup lang="ts">
import { ref } from "vue";

const msg = ref("Hello World");
</script>

<style scoped></style>
