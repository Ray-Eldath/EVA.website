<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'App',
    mounted: function () {
      $youziku.load(".font-dms", "e065314a24474f9a80dcf5c2eea41e8f", "DFGMincho-SU");
      $youziku.draw();
    }
  }

</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    margin-top: 60px;
  }

</style>
