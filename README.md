<h1>svg-new</h1>
<h2>The SVG 2 namespace is http://www.w3.org/2000/svg, which is the same as for earlier versions of SVG.</h2>
<h3>New background svg style.</h3>

```
<svg xmlns="http://www.w3.org/2000/svg"
     xmlns:xlink="http://www.w3.org/1999/xlink">
	 
  <text x="20" y="40">SVG text example</text>

  <text x="50" y="100">SVG text example</text>
  
  
</svg>
```

```
<div class="sp-container">
  <div class="sp-content">
    <div class="sp-globe"></div>
    <a class="sp-circle-link" href="https://www.youtube.com/@SilusGamingWorld1">by G'Pa</a>
  </div>
</div>


.sp-container {
  position: fixed;
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100%;
  z-index: 0;
  background: -webkit-radial-gradient(rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.3) 35%, rgba(0, 0, 0, 0.7));
  background: -moz-radial-gradient(rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.3) 35%, rgba(0, 0, 0, 0.7));
  background: -ms-radial-gradient(rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.3) 35%, rgba(0, 0, 0, 0.7));
  background: radial-gradient(rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.3) 35%, rgba(0, 0, 0, 0.7));
}
.sp-content {
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0px;
  top: 0px;
  z-index: 1000;
}

.sp-globe {
  position: absolute;
  width: 282px;
  height: 273px;
  left: 50%;
  top: 50%;
  margin: -137px 0 0 -141px;
  background: transparent url(http://web-sonick.zz.mu/images/sl/globe.png) no-repeat top left;
  -webkit-animation: fadeInBack 3.6s linear 14s backwards;
  -moz-animation: fadeInBack 3.6s linear 14s backwards;
  -ms-animation: fadeInBack 3.6s linear 14s backwards;
  animation: fadeInBack 3.6s linear 14s backwards;
  -ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=30)";
  filter: alpha(opacity=30);
  opacity: 0.3;
  -webkit-transform: scale(5);
  -moz-transform: scale(5);
  -o-transform: scale(5);
  -ms-transform: scale(5);
  transform: scale(5);
}


.sp-circle-link {
  position: absolute;
  left: 50%;
  bottom: 100px;
  margin-left: -50px;
  text-align: center;
  line-height: 100px;
  width: 100px;
  height: 100px;
  background: #fff;
  color: #3f1616;
  font-size: 25px;
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border-radius: 50%;
  -webkit-animation: fadeInRotate 1s linear 16s backwards;
  -moz-animation: fadeInRotate 1s linear 16s backwards;
  -ms-animation: fadeInRotate 1s linear 16s backwards;
  animation: fadeInRotate 1s linear 16s backwards;
  -webkit-transform: scale(1) rotate(0deg);
  -moz-transform: scale(1) rotate(0deg);
  -o-transform: scale(1) rotate(0deg);
  -ms-transform: scale(1) rotate(0deg);
  transform: scale(1) rotate(0deg);
}
.sp-circle-link:hover {
  background: #85373b;
  color: #fff;
}
```

