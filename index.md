
**Have you ever wonder what accounts follow you back on instagram?** <br>
Imagine you are logging into your Instagram (IG) account, suddenly you notice someone unfollow you 😡!!! Well... If you have 10 to 50 people following you, trying to find it manually by typing the account's names of the Following under the Followers tab is 🍰. However, it is super unpractical for someone with 100 followers and crazy for anyone over 500 followers to do so (please don't do it, you are better off taking your time to learn how to code and writing your own program). Besides your fingertips and your own desire to discover who betrayed you, the other resource available is third-party applications. I never used one, but my bias is that it is for the least super sketch to provide your information such as account name and password to anyone. So... 🥁 🥁 🥁

<p align=center> 🎉🎉 <strong>You are welcome! This website was developed for you!</strong> 🎉🎉 </p>

Here you will only need to provide two things, all you followers' account and all accounts you follow.

## Getting the info/data from IG 


<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
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

/* Caption text */
.text {
  color: #252c6a;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 12px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #252c6a;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
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


<div class="slideshow-container">

<div class="mySlides fade">
  <div>
  <div class="numbertext">1 / 3</div>
  <img src="https://raw.githubusercontent.com/roda-por-favor/Seguidores_Instagram/main/Imagens/Tela%20inicial%20instagram%20-%20settings.PNG" style="width:100%">
 </div>
 <div class="text"><strong> First go to the settings of your IG account </strong></div>
</div>
 


<div class="mySlides fade">
  <div>
  <div class="numbertext">2 / 3</div>
  <img src="https://raw.githubusercontent.com/roda-por-favor/Seguidores_Instagram/main/Imagens/instagram%20security.PNG" style="width:100%">
  </div>
  <div class="text"> <strong>Go to Privacy and Security</strong></div>
</div>

<div class="mySlides fade">
  <div>
  <div class="numbertext">3 / 3</div>
  <img src="https://raw.githubusercontent.com/roda-por-favor/Seguidores_Instagram/main/Imagens/account%20data%20instagram.PNG" style="width:100%">
  </div>
  <div class="text">At the botton access view account data</div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
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


## The Magic 


