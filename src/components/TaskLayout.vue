<template>
  <div class="container">
    <slot></slot>
  </div>
</template>

<style scoped>
.container {
  margin-top: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 550px;
  padding: 1rem;
  border: 1px solid rgba(255, 255, 255, 0.87);
  border-radius: 8px;
}
</style>