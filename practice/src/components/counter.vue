<script setup>
import { ref } from 'vue';

// Define a reactive state variable
const count = ref(0);

// Function to increase the count
const increment = () => {
  count.value++;
};
</script>

<template>
  <div>
    <h2>Counter: {{ count }}</h2>
    <button @click="increment">Increment</button>
  </div>
</template>

<style scoped>
button {
  padding: 8px 16px;
  font-size: 16px;
  margin-top: 10px;
}
</style>
