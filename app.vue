<template>
  <div>
    <div :class="[`min-h-[${minHeight}vh]`]"></div>
  </div>
</template>

<script setup lang="ts">
const minHeight = ref<number>(60)
</script>