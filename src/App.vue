<template>
  <div id="app">
    <h1>Becca's 2048</h1>
    <Board />
  </div>
</template>

<script>
import Board from './components/Board';

export default {
  name: 'app',
  components: {
    Board,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

* {
  box-sizing: border-box;
}
</style>
