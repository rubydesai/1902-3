<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<link rel="shortcut icon" type="image/x-icon" href="https://static.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico" />
<link rel="mask-icon" type="" href="https://static.codepen.io/assets/favicon/logo-pin-8f3771b1072e3c38bd662872f6b673a722f4b3ca2421637d5596661b4e2132cc.svg" color="#111" />
<title>CodePen - 1902-3</title>
<style>
    span {
  color:#FFFFFF;
}

div{
  background:#CCCCCC;
}
  </style>
</head>
<body translate="no">
<div>
<button id="playMe">Play Me</button>
<button id="playFast">Play Fast</button>
<button id="playFromMiddle">Play From Middle</button>
</div>
<video width="400" id="myVideo" controls>
<source src="https://github.com/seattleacademy/1902-3/raw/master/video/myvideo.mp4" type="video/mp4">
Your browser does not support HTML5 video.
</video>
<div>Hello <span>World</span></div>
<script id="rendered-js">
      console.clear();

vid = document.getElementById("myVideo");
document.getElementById("playMe").addEventListener("click",playMe);
document.getElementById("playFast").addEventListener("click",playFast);
document.getElementById("playFromMiddle").addEventListener("click",playFromMiddle);

function playMe(e){
  console.log("Button Clicked");
  vid.playbackRate = .5;
  vid.play();
}

function playFast(e){
  vid.playbackRate = 2;
  vid.play();
}

function playFromMiddle(e){
  vid.currentTime = 5;
  vid.play();
}
    </script>
</body>
</html>

