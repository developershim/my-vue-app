<template>
  <main class="app">
    <h1>Hello from Vue 3 + Vite!</h1>
    <p>This is a sample Vue app deployed via Vercel and Netlify.</p>

    <button @click="count++">
      Clicked {{ count }} times
    </button>
  </main>
</template>

<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>

<style scoped>
.app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  margin-top: 4rem;
}
button {
  margin-top: 1rem;
  padding: 0.5rem 1rem;
  border: none;
  background-color: #42b883;
  color: white;
  font-size: 1rem;
  border-radius: 8px;
  cursor: pointer;
}
button:hover {
  background-color: #2c9b6f;
}
</style>
