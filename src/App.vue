<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TaskLayout> 
      <GameBoard />
    </TaskLayout>
  </div>
</template>

<script>
import GameBoard from './components/GameBoard.vue'
import TaskLayout from './components/TaskLayout.vue';

export default {
  name: 'App',
  components: {
    GameBoard,
    TaskLayout
  }
}
</script>

<style>
:root {
  font-family: system-ui, Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.5;
  font-weight: 400;

  color-scheme: light dark;
  color: rgba(255, 255, 255, 0.87);
  background-color: #242424;

  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 1rem;
  text-align: center;
}

p {
  margin: 0;
  text-align: start;
}

.logo {
  height: 130px;
  padding: 1em;
}
</style>
