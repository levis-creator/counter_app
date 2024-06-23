<script setup lang="ts">
import Button from "./Button.vue";
</script>
<template>
  <div class="score_container">
    <h3>Team A</h3>
    <span class="score">0</span>
    <div class="score_btn">
      <Button>+1</Button>
      <Button>-1</Button>
    </div>
  </div>
</template>
<style scoped>
.score_container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 5em;
}
.score {
  font-family: "Orbitron", sans-serif;
  font-size: 10em;
}
.score_btn {
  display: flex;
  gap: 2em;
}
</style>
