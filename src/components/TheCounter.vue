<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)

const addCount = () => {
  count.value += 1
}
</script>

<template>
  <button @click="addCount">Count: {{ count }}</button>
</template>

<style scoped></style>
