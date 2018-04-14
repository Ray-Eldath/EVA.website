<template>
  <div>
    <NavBar/>
    <div id="fullpage">
      <div class="section">
        <h1>啦啦啦</h1>
      </div>
      <div class="section">Some section</div>
      <div class="section">Some section</div>
      <div class="section">Some section</div>
    </div>
  </div>
</template>

<style scoped>
  #fullpage {
    margin-top: -60px;
  }

</style>
<script>
  import NavBar from '../components/NavBar'
  export default {
    components: {
      NavBar
    },
    mounted: function () {
      $('#fullpage').fullpage({
        sectionsColor: ['#1bbc9b', '#4BBFC3', '#7BAABE', 'whitesmoke', '#ccddff'],
        anchors: ['firstPage', 'secondPage', '3rdPage', '4thpage', 'lastPage'],
        menu: '#menu',
        navigation: true,
        continuousVertical: true,
        scrollingSpeed: 1000
      });
    }
  }

</script>
