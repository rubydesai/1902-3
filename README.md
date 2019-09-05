<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<link rel="shortcut icon" type="image/x-icon" href="https://static.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico" />
<link rel="mask-icon" type="" href="https://static.codepen.io/assets/favicon/logo-pin-8f3771b1072e3c38bd662872f6b673a722f4b3ca2421637d5596661b4e2132cc.svg" color="#111" />
<title>CodePen - 1902-3</title>
<style>
    span {
  color:#ffffff;
}
div{
  background:#CCCCCC;
}
  </style>
</head>
<body translate="no">
<div>
<button id="playMe">PlayMe</button>
<button id="playFast">Play Fast</button>
</div>
<video width="400" id="myVid" height="240" controls>
<source src="https://github.com/rubydesai/1902-3/raw/master/video%20for%20software.html" type="video/mp4">
<source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
<div>Hello <span>World</span></div>
<script id="rendered-js">
      console.clear();
year x=5;
console.log("hello world",x);
document.getElementById("playMe").addEventListener("click", playMe);

function playMe(e){
  console.log("Button Clicked");
  var vid = document.getElementById("myVideo"); 
}
vid=document.getElementById("anyVideo");
    </script>
</body>
</html>
