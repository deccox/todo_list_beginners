<script setup lang="ts">
import HeaderC from '../src/components/HeaderC.vue';
import BoardC from '../src/components/BoardC.vue';

</script>

<template>
  <div class="main-container">
    <HeaderC/>
    <BoardC/>
  </div>
</template>

<style>
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-weight: normal;
}

body{
  padding: 0;
  margin: 0;
}
.main-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: auto;
  padding: 0;
  min-height: 100vh;
  font-family:
    Inter;
  font-size: 1em;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

</style>
