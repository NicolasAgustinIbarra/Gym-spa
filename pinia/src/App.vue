<template lang="es">
  <h3>{{store.count}} x 2 = {{store.time2}}</h3>
  <button @click="store.increment(1)">increment</button>
</template>

<script setup>
  import { useCounterStore } from './store/Counter';

  const store = useCounterStore();
  store;
  

  
  
</script>