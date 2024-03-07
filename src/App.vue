<script setup>
  import { ref } from "vue"; // importa la posibilidad de hacer variables reactivas
  const count = ref(0);
</script>

<template>
 <button>Test</button>
</template>

<style scoped>
button {
  background-color: var(--bg-color-button);
  color: var(--color-button);
}
</style>
