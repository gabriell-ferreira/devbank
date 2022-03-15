<template>
  <div id="app">
    <Banner></Banner>
  </div>
</template>

<script>

import Banner from '@/components/Banner.vue';

export default {
  name: 'App',
  components: {
    Banner
  }
}
</script>

<style>
  * {
    box-sizing: border-box;
    margin: 0;
  }

  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #000000;
    height: 100vh;
    width: 100vw;
  }
</style>
