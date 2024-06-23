<script setup lang="ts">
import Team from "./components/Team.vue";
</script>
<template>
  <h1 class="main_head">Score board</h1>
  <div class="container">
    <div class="team">
      <Team />
    </div>
    <div class="team">
      <Team />
    </div>
  </div>
</template>
<style scoped>
.main_head {
  text-align: center;
}
.container {
  display: flex;
}
.team {
  flex: 1;
}
</style>
