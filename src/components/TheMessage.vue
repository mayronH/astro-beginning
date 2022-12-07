<script setup lang="ts">
defineProps({
  message: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div>{{ message }}</div>
</template>

<style scoped>
div {
  padding: 0.5rem;
  border-radius: 0.5rem;
  background: #eee;

  color: lime;
}
</style>
