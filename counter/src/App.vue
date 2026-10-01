<script setup>
import { ref } from "vue";

const count = ref(0);
</script>

<template>
  <div>
    <p>Current Count: {{ count }}</p>
    <button @click="count++">Increase Count</button>
  </div>
</template>
