---

title: "Family"
permalink: /family/
author_profile: true

---


<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 500px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}


/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 6px;
  width: 6px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>

<h2>Memories with the Fam Jam...</h2>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/7.JPG" style="width:100%">
  
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/8.JPG" style="width:100%">
  
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/9.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/10.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/11.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/12.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/13.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/14.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/15.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/16.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/17.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/18.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/19.JPG" style="width:100%">
 
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/20.JPG" style="width:100%">
 
</div>
  
<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/Fam 1.jpeg" style="width:100%">
 
</div>
  
<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/Fam 2.jpeg" style="width:100%">
 
</div>
  
<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/Fam 3.jpeg" style="width:100%">
 
</div>
  
<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/Fam 4.jpeg" style="width:100%">
 
</div>
  
<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="/images/Fam 5.jpeg" style="width:100%">
 
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
  <span class="dot" onclick="currentSlide(4)"></span> 
  <span class="dot" onclick="currentSlide(5)"></span> 
  <span class="dot" onclick="currentSlide(6)"></span> 
  <span class="dot" onclick="currentSlide(7)"></span> 
  <span class="dot" onclick="currentSlide(8)"></span> 
  <span class="dot" onclick="currentSlide(9)"></span> 
  <span class="dot" onclick="currentSlide(10)"></span> 
  <span class="dot" onclick="currentSlide(11)"></span> 
  <span class="dot" onclick="currentSlide(12)"></span> 
  <span class="dot" onclick="currentSlide(13)"></span> 
  <span class="dot" onclick="currentSlide(14)"></span> 
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>

</body>
</html> 


<iframe width="966" height="543" src="https://www.youtube.com/embed/NBCLKNoghu8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
