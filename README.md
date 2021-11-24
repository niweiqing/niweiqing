### Hi there 👋
Skip to content
Search or jump to…
Pull requests
Issues
Marketplace
Explore
 
@niweiqing 
niweiqing
/
qiuqiu
Public
1
00
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
qiuqiu/可心.html
@niweiqing
niweiqing Add files via upload
Latest commit ba12311 9 minutes ago
 History
 1 contributor
399 lines (383 sloc)  16 KB
   
<!DOCTYPE html>
<html>

<script src="js/clipboard.js"></script>
<script>
   var clipboard = new ClipboardJS('.fuzhitkl');

   clipboard.on('success', function (e) {
      console.log(e);
   });

   clipboard.on('error', function (e) {
      console.log(e);
   });
</script>

<head>
   <meta charset="utf-8">
   <title>love</title>
   <meta name="keywords" content="XX" />
   <meta name="description" content="XX" />
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <link href="css/bootstrap.css" rel="stylesheet" type="text/css" media="all" />
   <link href="css/base.css" rel="stylesheet" type="text/css" media="all" />
   <link href="css/main.css" rel="stylesheet" type="text/css" media="all" />
   <link href="css/venobox.css" rel="stylesheet" type="text/css" media="all" />
   <link href="css/fonts.css" rel="stylesheet" type="text/css" media="all" />
   <link href="css/ae168344b8194b348b667f19ac4d1956.css" rel="stylesheet">
</head>

<body>
   <div class="loader">
      <div class="loader-inner">
         <svg width="120" height="220" viewbox="0 0 100 100" class="loading-spinner" version="1.1"
            xmlns="http://www.w3.org/2000/svg">
            <circle class="spinner" cx="50" cy="50" r="21" fill="#ffffff" stroke-width="2" />
         </svg>
      </div>
   </div>
   <div class="wrapper">
      <section class="hero overlay">
         <div class="background-img">
            <img src="picture/17.jpg" alt="">
         </div>
         <header class="header default">
            <div class=" left-part">
               <a class="logo scroll" href="#hero">
                  <h2>LOVE</h2>
               </a>
            </div>
            <div class="right-part">
               <nav class="main-nav">
                  <div class="toggle-mobile-but">
                     <a href="#" class="mobile-but">
                        <div class="lines"></div>
                     </a>
                  </div>
                  <ul>
                     <li><a class="scroll" href="#home">球球</a></li>
                     <li><a class="scroll" href="#story">球球</a></li>
                     <li><a class="scroll" href="#album">球球</a></li>
                  </ul>
               </nav>
            </div>
         </header>
         <div class="inner-hero">
            <div class="container hero-content">
               <div class="row">
                  <div class="col-sm-12 text-center">
                     <h1 class="large mb-20">LOVE</h1>
                     <div class="block-date-hero">
                        <div class="circle-dashed bg-n">
                           <div class="round-circle">
                              <svg viewBox="0 0 103 103" version="1.1" xmlns="http://www.w3.org/2000/svg"
                                 class="dashed-border">
                                 <circle cx="50%" cy="50%" r="50" />
                              </svg>
                              <i class="icon-heart"></i>
                           </div>
                        </div>
                        <ul>
                           <li>NWQ</li>
                           <li>QJF</li>
                        </ul>
                     </div>
                     <p class="mt-20 lead"></p>
                  </div>
               </div>
            </div>
         </div>
      </section>
      <section id="story" class="story pt-120 pb-120">
         <svg class="section-dashed" version="1.1" xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" width="50px" height="578px" xml:space="preserve">
            <path class="dashed-line" stroke-width="1" d="M30 0 v600 400" />
         </svg>
         <div class="container">
            <div class="row">
               <div class="col-sm-12 text-center mb-100">

                  <h1 class="title">Our love story</h1>
                  <p>The Story of our love</p>
               </div>
               <div class="background-img">
                  <img src="picture/1.jpeg" alt="">
               </div>
            </div>
            <div class="row">
               <div class="col-md-4 col-md-offset-4 col-sm-8 col-sm-offset-2 text-center mb-30">
                  <h2 class="heavy">球球<br><span>球球</span></h2>
               </div>
            </div>
            <div class="row story-row mt-100 mb-100">
               <div class="circle-dashed timeline bg">
                  <div class="round-circle bg before">
                     <svg viewBox="0 0 103 103" version="1.1" xmlns="http://www.w3.org/2000/svg" class="dashed-border">
                        <circle cx="50%" cy="50%" r="50" />
                     </svg>
                     <i class="icon-heart"></i>
                  </div>
               </div>
               <div class="col-sm-5 ">
                  <div class="couple-story text-right">
                     <p>球球</p>
                  </div>
               </div>
               <div class="col-sm-5 col-sm-offset-2">
                  <div class="couple-story">
                     <p>球球</p>
                  </div>
               </div>
            </div>
            <div class="row story-row mt-100 mb-80 ">
               <div class="circle-dashed timeline bg green">
                  <div class="round-circle  green before">
                     <svg viewBox="0 0 103 103" version="1.1" xmlns="http://www.w3.org/2000/svg" class="dashed-border">
                        <circle cx="50%" cy="50%" r="50" />
                     </svg>
                     <i class="icon-heart"></i>
                  </div>
               </div>
               <div class="col-sm-5 ">
                  <div class="couple-story text-right">
                     <p>球球</p>
                  </div>
               </div>
               <div class="col-sm-5 col-sm-offset-2">
                  <div class="couple-story">
                     <p>球球</p>
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-12  text-center mt-100">
                  <a href="#" class="but">
                     <span>球球</span>
                     <svg class="but-svg" width="175" height="50" viewBox="0 0 415 120"
                        xmlns="http://www.w3.org/2000/svg">
                        <rect class="but-rect" x="10" y="10" width="400" height="100" rx="6" ry="6" />
                     </svg>
                  </a>
               </div>
            </div>
         </div>
      </section>
      <section class="date pt-150 pb-150 overlay">
         <div class="background-img">
            <img src="picture/4.jpg" alt="">
         </div>
         <div class="container">
            <div class="row">
               <h2 class="indent">Wedding date</h2>
               <div class="col-sm-12 text-center">
                  <div class="block-content front-p">

                     <h2 class="typo">Save the date</h2>
                     <span id="elapseClock" class="text-white" style="font-size: 45px;font-weight: 300;">days <span
                           class="digit">20</span> hours <span class="digit">14</span> minutes <span
                           class="digit">00</span> seconds</span>
                  </div>
               </div>
            </div>
         </div>
      </section>
      <section id="album" class="album bg-grey pt-120 pb-120">
         <div class="container">
            <div class="row">
               <div class="col-sm-12 text-center mb-100">
                  <h1 class="title">球球</h1>
                  <p>Main ceremony - Wedding party</p>
               </div>
            </div>
            <div class="row mb-30">
               <h2 class="indent">Photo album</h2>
               <div class="col-md-4 col-sm-4 col-xs-12 ">
                  <div class="block-img">
                     <a href="http://img.zxgnz.com/images/20190804/cb826eac7cbe770ee7de6b6b97dbd7a.jpg" class="venobox">
                        <div class="background-img">
                           <img alt="" src="picture/cb826eac7cbe770ee7de6b6b97dbd7a.jpg">
                        </div>
                     </a>
                  </div>
               </div>
               <div class="col-md-4 col-sm-4 col-xs-12 ">
                  <div class="block-img">
                     <a href="http://img.zxgnz.com/images/20190804/359095d8113c9cfac9900b8870fd5d7.jpg" class="venobox">
                        <div class="background-img">
                           <img alt="" src="picture/359095d8113c9cfac9900b8870fd5d7.jpg">
                        </div>
                     </a>
                  </div>
               </div>
               <div class="col-md-4 col-sm-4 col-xs-12 ">
                  <div class="block-img">
                     <a href="http://img.zxgnz.com/images/20190804/5fef2731eded00965ce161ca1052ffa.jpg" class="venobox">
                        <div class="background-img">
                           <img alt="" src="picture/5fef2731eded00965ce161ca1052ffa.jpg">
                        </div>
                     </a>
                  </div>
               </div>
               <div class="col-md-4 col-sm-4 col-xs-12">
                  <div class="block-img">
                     <a href="http://img.zxgnz.com/images/20190804/54d179bf367c8b015ef85046ef76e34.jpg" class="venobox">
                        <div class="background-img">
                           <img alt="" src="picture/54d179bf367c8b015ef85046ef76e34.jpg">
                        </div>
                     </a>
                  </div>
               </div>
               <div class="col-md-4 col-sm-4 col-xs-12 ">
                  <div class="block-img">
                     <a href="http://img.zxgnz.com/images/20190804/bbda43833f6cc0fe971885db9a746ba.jpg" class="venobox">
                        <div class="background-img">
                           <img alt="" src="picture/bbda43833f6cc0fe971885db9a746ba.jpg">
                        </div>
                     </a>
                  </div>
               </div>
               <div class="col-md-4 col-sm-4 col-xs-12 ">
                  <div class="block-img">
                     <a href="http://img.zxgnz.com/images/20190804/2ef3ee9455da992b2eef3affbf560be.jpg" class="venobox">
                        <div class="background-img">
                           <img alt="" src="picture/2ef3ee9455da992b2eef3affbf560be.jpg">
                        </div>
                     </a>
                  </div>
               </div>
            </div>
         </div>
      </section>
      <section class="just-married pt-200 pb-200 overlay">
         <div class="background-img">
            <img src="picture/17.jpg" alt="">
         </div>
         <div class="container">
            <div class="row">
               <div class="col-sm-12 text-center">
                  <div class="block-content front-p">
                     <h2 class="typo">❤</h2>
                     <h2 class="heavy uppercase mt-10 light">球球</h2>
                  </div>
               </div>
            </div>
         </div>
      </section>
      <footer class="footer pt-70 pb-70">
         <div class="container">
            <div class="row">
               <div class="col-sm-12 text-center">
                  <p class="uppercase heavy normal">&copy; 2021 love.NWQ &QJF</p>
               </div>
            </div>
         </div>
      </footer>
   </div>
   <script src="js/jquery-1.12.4.min.js" type="text/javascript"></script>
   <script src="js/jquery.countdown.min.js" type="text/javascript"></script>
   <script src="js/venobox.min.js" type="text/javascript"></script>
   <script src="js/smooth-scroll.js" type="text/javascript"></script>
   <script src="js/script.js" type="text/javascript"></script>
   <script type="text/javascript">
      var together = new Date();
      var strs = "2021-11-04";
      var nowTime = new Date();
      var together = new Date(strs.replace(/-/g, "/"));
      timeElapse(together);
      setInterval(function () { timeElapse(together); }, 500);
      function timeElapse(c) {
         var e = Date();
         var f = (Date.parse(e) - Date.parse(c)) / 1000;
         var g = Math.floor(f / (3600 * 24)); f = f % (3600 * 24);
         var b = Math.floor(f / 3600);
         if (b < 10) { b = "0" + b } f = f % 3600; var d = Math.floor(f / 60);
         if (d < 10) { d = "0" + d } f = f % 60;
         if (f < 10) { f = "0" + f }
         var a = '<span class="digit">' + g + '</span> days <span class="digit">' + b + '</span> hours <span class="digit">' + d + '</span> minutes <span class="digit">' + f + "</span> seconds"; $("#elapseClock").html(a)
      };
   </script>


   <link rel="stylesheet" href="css/cuplayer.css">
   <div style="position:absolute; top:50px; right:50px;">
      <audio id="main_audio" autoplay="autoplay" preload="auto" loop>
         <source src="http://www.zaiyiqiba.com/mp3/kgmp3.php?id=de7a6d73d7caa0e8962fd29f4e2162ef" type="audio/mpeg" />
      </audio>
      <a class="c-white fs-12 icon-play rotate" id="btn-play" href="javascript:void(0);"></a>
   </div>
   <script type="text/javascript">
      //获取picid函数
      $(function () {
         $("area").click(function () {
            var picId = $(this).attr("data-id");
            var picSrc = "images/img_big/" + picId + ".jpg"
            $(".modal-content>.pic-box>img").attr("src", picSrc);
         })
         var isPlaying = function (audio) { return !audio.paused; }
         var a = document.getElementById('main_audio');
         $('#btn-play').on('click', function () {
            if ($(this).hasClass('rotate')) {
               a.pause();
               $(this).removeClass('rotate');
            } else {
               a.play();
               $(this).addClass('rotate');
            }
         });

      })
   </script>
   <script src="js/jweixin-1.0.0.js"></script>
   <script>
      function autoPlayAudio1() {
         wx.config({
            // 配置信息, 即使不正确也能使用 wx.ready
            debug: false,
            appId: '',
            timestamp: 1,
            nonceStr: '',
            signature: '',
            jsApiList: []
         });
         wx.ready(function () {
            document.getElementById('main_audio').play();
         });
      }
      autoPlayAudio1(); // 推荐使用方法1
   </script>
   <bgsound src="http://www.51bbw.cn/mp3/1youdiantian.mp3" loop="-1" />
   <audio src="http://www.51bbw.cn/mp3/1youdiantian.mp3" controls autoplay='autoplay' loop="loop" id="bgmusic"
      style="display:none"></audio>
   <script>
      (function () {
         function log(info) {
            console.log(info);
            // alert(info);
         }
         function forceSafariPlayAudio() {
            audioEl.load(); // iOS 9   还需要额外的 load 一下, 否则直接 play 无效
            audioEl.play(); // iOS 7/8 仅需要 play 一下
         }

         var audioEl = document.getElementById('bgmusic');

         audioEl.addEventListener('loadstart', function () {
            log('loadstart');
         }, false);
         audioEl.addEventListener('loadeddata', function () {
            log('loadeddata');
         }, false);
         audioEl.addEventListener('loadedmetadata', function () {
            log('loadedmetadata');
         }, false);
         audioEl.addEventListener('canplay', function () {
            log('canplay');
         }, false);
         audioEl.addEventListener('play', function () {
            log('play');
            // 当 audio 能够播放后, 移除这个事件
            window.removeEventListener('touchstart', forceSafariPlayAudio, false);
         }, false);
         audioEl.addEventListener('playing', function () {
            log('playing');
         }, false);
         audioEl.addEventListener('pause', function () {
            log('pause');
         }, false);

         // 由于 iOS Safari 限制不允许 audio autoplay, 必须用户主动交互(例如 click)后才能播放 audio,
         // 因此我们通过一个用户交互事件来主动 play 一下 audio.
         window.addEventListener('touchstart', forceSafariPlayAudio, false);

         audioEl.src = "http://www.51bbw.cn/mp3/1youdiantian.mp3";
      })();
   </script>

</body>

</html>
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete
