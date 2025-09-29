<script setup lang="ts">
import Vue from 'vue';

Vue.component('GaveBoard', {
  data() {
  },
});
</script>
<template>
  <img :src="require('@/assets/example.png')" alt="Example" class="example" />
</template>
<style scoped>
.example {
  height: 100%;
  width: 100%;
  object-fit: contain;
}
</style>