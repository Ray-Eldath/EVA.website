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
          <div class="background full" style="background-image: url('https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/411840.png')"></div>
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
            <span class="emphasize">是日本历史上少有能带来广泛社会影响的现象级作品，被公认为日本最伟大的ACG作品之一</span>。作品应用了当时颇具革命性的意识流手法，扑朔迷离、庞大复杂的故事情节，以及大量的神秘学、哲学、心理学概念，以及宗教符号的使用，都使其在日本国内和国际上引起了巨大反响和争议，并
            <span class="emphasize">成为日本动画史上的一座里程碑</span>。
            <br/> 作品初期注重描写人物对话及战斗描写，通过情节的推进开始着重于人物内心的叙述。在TV版的后期阶段，借助强烈象征意味的画面与配音的闪现，以此表现精神分析性的叙述可以说是本作的标志。在TV放送后，日本产生“社会现象”规模的巨大回响与冲击，《新世纪福音战士》也成为当时的热议话题。而今即便在新剧场版陆续放出的现在，仍然拥有广泛的衍生品商品和火爆的人气。
          </p>
        </div>
        <div>
          <div class="background full" style="background-image: url('https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/837568.jpg')"></div>
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
            突袭世界的大灾难
            <span class="emphasize">“第二次冲击”</span>后，世界在废墟之上重建。14岁的少年
            <span class="emphasize">碇真嗣</span>被父亲碇元渡叫到第三新东京市。本以为能见到父亲迎接的他，却见到名为
            <span class="emphasize">“使徒”</span>的巨大生物与军队交火。危急之下，特务机关NERV的葛成美里将真嗣救下，并将其带往碇元渡所统领的NERV总部。但迎接真嗣的，却是是父亲冷酷地命令：驾驶
            <span class="emphasize">称为“EVA”的巨大人型机器人</span>与使徒战斗。本已表示拒绝的真嗣，看到重伤的替补驾驶员绫波丽后，决定遵从父亲的命令。就这样，从未受过作战训练的真嗣，准备驾驶EVA初号机迎战使徒。
            <br/>不断袭来的使徒，身份不明的绫波丽，从德国来的驾驶员惣流·明日香·兰格蕾，14岁的少年要面对远超自己能力的挑战。而碇元渡不动声色地观察一切，一个称为
            <span class="emphasize">“人类补完计划”</span>的神秘计划正在按照他的计划实现。
          </p>
        </div>
        <div>
          <div class="background full" style="background-image: url('https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/evangelion-20-wallpaper.jpg')"></div>
          <div class="cover full"></div>
        </div>
      </div>
      <div class="section fourth">
        <div class="content ui four column equal width centered grid full">
          <div class="column animated">
            <img src="https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/eva01.png">
          </div>
          <div class="column animated">
            <img src="https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/eva01.png">
          </div>
          <div class="column animated">
            <img src="https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/eva01.png">
          </div>
          <div class="column animated">
            <img src="https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/eva01.png">
          </div>
        </div>
        <div>
          <div class="background full" style="background-image: url('https://gitee.com/Ray-Eldath/Image/raw/master/Image/EVA.website/837568.jpg')"></div>
          <div class="cover full"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .fourth .content>div:hover {
    border-color: white;
    z-index: 10;
  }

  .fourth .content>div {
    height: 100%;
    margin-top: 15px;
    border: black solid 10px;
    margin-left: -10px;
  }

  .fourth .content {
    margin-left: 10px;
    padding-right: 10px;
  }

  .third .text span[class=emphasize] {
    border-bottom: 1px solid;
  }

  .third .story p {
    opacity: .9 !important;
  }

  .third .text {
    margin-left: 40px;
    width: 620px;
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

  .second .text span[class=emphasize] {
    color: rgb(255, 130, 130);
    opacity: 1;
    font-weight: 800;
    border-bottom: 1px solid;
  }

  .second .cover {
    opacity: .65 !important;
  }

  .text span[class=emphasize] {
    margin-left: -10px;
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

  .first .cover {
    opacity: .1 !important;
  }

  .section .cover {
    background-color: black;
    opacity: .6;
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
      var fourthAnimated = $('.fourth .animated')
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
          // 1 -> 2 || 1 -> ]
          if (index == 1 && (direction == 'down') || direction == 'up') {
            nav.fadeIn(1400)
          }
          // 1 -> 2
          if (index == 1 && direction == 'down') {
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
          // 3 -> 4
          if (index == 3 && direction == 'down') {
            fourthAnimated.eq(0).addClass('animated fadeInUp')
            fourthAnimated.eq(1).addClass('animated fadeInUp')
            fourthAnimated.eq(2).addClass('animated fadeInDown')
            fourthAnimated.eq(3).addClass('animated fadeInDown')
            fourthAnimated.eq(1).css('animation-delay', '.6s')
            fourthAnimated.eq(0).css('animation-delay', '.9s')
            fourthAnimated.eq(2).css('animation-delay', '1.1s')
            fourthAnimated.eq(3).css('animation-delay', '1.4s')
            return
          }
        }
      })
    }
  }

</script>
