<template>
  <div id="app">
    <button @click="count++">Count is: {{ count }}</button>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)
</script>