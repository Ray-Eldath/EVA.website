<template>
  <div>
    <NavBar/>
    <div id="fullpage">
      <div class="section first">
        <div style="z-index: 1000">
          <img src="../assets/logo.png">
          <h1 class="header font-dms">Evangelion</h1>
          <div class="meta">
            <p class="font-dms">
              # 新世纪福音战士
              <br/># 新世纪エヴァンゲリオン
            </p>
          </div>
        </div>
        <div>
          <div class="background full" style="background-image: url('https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/evangelion-20-wallpaper.jpg')"></div>
          <div class="cover full"></div>
        </div>
      </div>
      <div class="section second">
        <div>
          <h1 class="font-dms">故事 Story</h1>
        </div>
        <div class="animated left">
          <img src="https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/eva01.png">
        </div>
        <div class="animated right">
          <img src="https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/Sachieldesign.png">
        </div>
        <div>
          <div class="background full" style="background-image: url('https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/bg-flat.png')"></div>
          <div class="cover full"></div>
        </div>
      </div>
      <div class="section">Some section</div>
      <div class="section">Some section</div>
    </div>
  </div>
</template>

<style scoped>
  .second .left {
    margin-top: 8px;
    margin-left: -20px;
  }

  .second .right img {
    width: 260px;
    height: 600px;
  }

  .second .right {
    margin-top: 14px;
    margin-right: 10px;
  }

  .second img {
    width: 70%;
  }

  .first .header {
    font-size: 50px;
    margin-top: -20px;
    font-weight: 400;
    color: white;
    opacity: .86;
  }

  .first .meta {
    margin-left: auto;
    margin-right: auto;
    width: 230px;
  }

  .first .meta p {
    color: white;
    opacity: .7;
    font-size: 20px;
    line-height: 1.1;
    text-align: left;
    margin-top: -12px;
    font-weight: 400;
    width: 100%;
  }

  .first img {
    opacity: .9;
  }

  .section .background {
    background-position: center;
    background-size: 100% auto;
    z-index: -5;
  }

  .section .cover {
    background-color: black;
    opacity: .3;
    z-index: -1;
  }

  .full {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
  }

  .left {
    position: absolute;
    top: 0;
    left: 0;
  }

  .right {
    position: absolute;
    top: 0;
    right: 0;
  }

  .section {
    z-index: -10;
  }

  #fullpage {
    margin-top: -60px;
  }

  #nav-bar {
    display: none;
  }

</style>
<script>
  import NavBar from '../components/NavBar'
  export default {
    components: {
      NavBar
    },
    mounted: function () {
      var secondAnimated = $('.second .animated')
      var nav = $('#nav-bar')
      $('#fullpage').fullpage({
        sectionsColor: ['#1bbc9b', '#4BBFC3', '#7BAABE', 'whitesmoke', '#ccddff'],
        anchors: ['first', 'second', 'third', 'forth'],
        menu: '#menu',
        navigation: true,
        continuousVertical: true,
        lockAnchors: true,
        scrollingSpeed: 1000,
        onLeave: function (index, nextIndex, direction) {
          // 1 -> 2
          if (index == 1 && direction == 'down') {
            nav.fadeIn('slow')
            secondAnimated.eq(0).addClass('animated fadeInLeftBig')
            secondAnimated.eq(1).addClass('animated fadeInRightBig')
            secondAnimated.eq(0).css('animation-delay', '.3s')
            secondAnimated.eq(1).css('animation-delay', '.6s')
            return
          }
          // * -> 1
          if (nextIndex == 1) {
            nav.fadeOut()
            return
          }
        }
      })
    }
  }

</script>
