<script setup lang="ts">
import Heading from "@/components/Heading.vue";
</script>

<template>
  <div class="page">
    <Heading/>
  </div>
</template>

<style>
@import url("./vendor/normalize.css");
@import url("./vendor/fonts.css");

.page {
  font-family: Manrope, Arial, sans-serif;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-text-size-adjust: 100%;
  -ms-text-size-adjust: 100%;
  -moz-text-size-adjust: 100%;
  font-size: 16px;
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
  height: 100vh;
}
</style>
