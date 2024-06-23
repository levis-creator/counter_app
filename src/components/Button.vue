<script setup lang="ts">
const props = defineProps<{ className?: string }>();
</script>

<template>
  <button :class="className">
    <slot />
  </button>
</template>
<style scoped>
button {
  padding: 1em 4em;
}
</style>
