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
        <div class="animated logo">
          <p>
            <img src="https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/Evangelion_Logo.png">
          </p>
          <p>
            <img src="../assets/logo.png">
          </p>
        </div>
        <div class="animated text intro">
          <h1 class="font-dms"># 简介 Intro</h1>
          <p class="font-sung content">
            《新世纪福音战士》，简称EVA。由庵野秀明导演，包括由GAINAX制作的TV版和旧剧场版以及由Studio Khara制作的新剧场版，全系列包含漫画、游戏、周边、电影等衍生作品。
            <br/>《新世纪福音战士》
            <emphasize>是日本历史上少有能带来广泛社会影响的现象级作品，被公认为日本最伟大的ACG作品之一</emphasize>。作品应用了当时颇具革命性的意识流手法，扑朔迷离、庞大复杂的故事情节，以及大量的神秘学、哲学、心理学概念，以及宗教符号的使用，都使其在日本国内和国际上引起了巨大反响和争议，并
            <emphasize>成为日本动画史上的一座里程碑</emphasize>。
            <br/> 作品初期注重描写人物对话及战斗描写，通过情节的推进开始着重于人物内心的叙述。在TV版的后期阶段，借助强烈象征意味的画面与配音的闪现，以此表现精神分析性的叙述可以说是本作的标志。在TV放送后，日本产生“社会现象”规模的巨大回响与冲击，《新世纪福音战士》也成为当时的热议话题。而今即便在新剧场版陆续放出的现在，仍然拥有广泛的衍生品商品和火爆的人气。
          </p>
        </div>
        <div>
          <div class="background full" style="background-image: url('https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/bg-flat.png')"></div>
          <div class="cover full"></div>
        </div>
      </div>
      <div class="section third">
        <div class="animated left">
          <img src="https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/eva01.png">
        </div>
        <div class="animated right">
          <img src="https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/Sachieldesign.png">
        </div>
        <div class="animated text story">
          <h1 class="font-dms"># 故事 Story</h1>
          <p class="font-sung">
            这是一个故事。
          </p>
        </div>
        <div>
          <div class="background full" style="background-image: url('https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/bg-flat.png')"></div>
          <div class="cover full"></div>
        </div>
      </div>
      <div class="section">Some section</div>
    </div>
  </div>
</template>

<style scoped>
  .second .text emphasize {
    color: rgb(255, 130, 130);
    opacity: 1;
    font-weight: 800;
    border-bottom: 1px solid;
  margin-left: -8px;
  }

  .second .text .content {
    opacity: .9;
  }

  .second .text {
    margin-left: 33%;
    position: relative;
    top: -36px;
    left: 130px;
    width: 700px;
  }

  .second .logo {
    position: absolute;
    top: 94px;
    left: 54px;
  }

  .second .logo img {
    width: 520px;
    height: auto
  }

  .text h1 {
    font-size: 46px
  }

  .text p {
    font-weight: 100;
    font-size: 20px;
    margin-top: -10px;
    margin-left: 54px;
  }

  .text {
    text-align: left;
    color: white;
  }

  .third .story {
    position: absolute;
    top: 10%;
    left: 22%;
  }

  .third .left {
    margin-top: 8px;
    margin-left: -20px;
  }

  .third .right img {
    width: 260px;
    height: 600px;
  }

  .third .right {
    margin-top: 14px;
    margin-right: 10px;
  }

  .third img {
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

  .font-sung {
    font-family: serif
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
      var thirdAnimated = $('.third .animated')
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
          // * -> 1
          if (nextIndex == 1) {
            nav.fadeOut()
            return
          }
          // 1 -> 2
          if (index == 1 && direction == 'down') {
            nav.fadeIn(1400)
            secondAnimated.eq(0).addClass('animated fadeIn')
            secondAnimated.eq(1).addClass('animated bounceInLeft')
            secondAnimated.eq(0).css('animation-delay', '1s')
            secondAnimated.eq(1).css('animation-delay', '1.8s')
            return
          }
          // 2 -> 3
          if (index == 2 && direction == 'down') {
            thirdAnimated.eq(0).addClass('animated fadeInLeftBig')
            thirdAnimated.eq(1).addClass('animated fadeInRightBig')
            thirdAnimated.eq(2).addClass('animated fadeInLeft')
            thirdAnimated.eq(0).css('animation-delay', '.3s')
            thirdAnimated.eq(1).css('animation-delay', '.8s')
            thirdAnimated.eq(2).css('animation-delay', '2s')
            return
          }
        }
      })
    }
  }

</script>
