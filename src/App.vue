<template>
  <v-app>
    <BTreeVisualizer />
  </v-app>
</template>

<script>

import BTreeVisualizer from './components/BTreeVisualizer.vue';

export default {
  name: 'App',
  components: {
    BTreeVisualizer,
  },
};
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    background-color: #edf2f7;
    min-height: 450px;
  }
  .name {
    font-size: 3rem;
    min-height: fit-content;
    height: 80px;
    line-height: 80px;
  }
</style>
