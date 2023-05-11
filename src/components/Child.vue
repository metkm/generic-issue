<script setup lang="ts" generic="T">
const modelValue = defineModel<T>();
</script>

<template>
  <input v-model="modelValue" />
</template>
