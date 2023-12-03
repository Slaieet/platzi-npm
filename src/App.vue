<script setup>
import { ref } from 'vue';


  let num = ref(0)

  const sumar = () => {
    num.value += 1
  }

</script>

<template>
  <main>
    <h1>Proyecto de vue js creado con vite usando npm</h1>
    <button @click="sumar">Contador: {{ num }}</button>
  </main>
</template>

<style scoped>

main {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

h1 {
  font-size: 2rem;
}

</style>
