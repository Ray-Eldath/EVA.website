<template>
  <div id="nav-bar">
    <div class="content">
      <div class="ui inverted segment inner">
        <div class="ui inverted secondary pointing menu">
          <div class="item icon">
            <img src="../assets/logo.png" alt="Evangelion">
          </div>
          <a class="active item">Home</a>
          <a class="item">Messages</a>
          <a class="item">好友</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  #nav-bar {
    position: fixed;
    width: 100%;
    bottom: 20px;
    overflow: hidden;
    z-index: 10000;
  }

  #nav-bar .content {
    height: 80px;
    line-height: 100px;
    width: 500px;
    margin-left: auto;
    margin-right: auto;
    background-color: black;
    border-radius: 40px;
    display: table;
  }

  .inner {
    background: transparent !important;
    display: table-cell;
    vertical-align: middle;
  }

  .inner .menu{
    border: 0;
    border-bottom: 0 !important;
  }

  .menu .icon {
    padding: 0 !important;
    margin-right: 20px !important;
    margin-left: 16px !important;
  }

  .menu .icon img {
    height: 40px;
    width: auto !important;
  }

</style>

<script>
  export default {}

</script>
