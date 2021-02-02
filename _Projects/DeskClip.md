---
layout: post
title: "WireManagment clips"
date: 2021-02-02
categories: [3d printing, 3d design, fusion 360]
image: /assets/Images/DeskClipMiddle.png
---
So, During this whole pandemic thing, me and my girlfriend decided we wanted a gaming computer, since we were gonn be stuck in our apartment anyway. This meant that our desk also needed some cablemanagment.

<!--more-->

unfortunately our desk did not have any cable manegment features, all the stores were closed, and i was not about to pay shipping for a 5 dollar cable rack.
This of course, was a job for my trusty old 3d printer. So i made and modeled 3 clips that snuggly fit in the back of my desk, 2 for each corner and one for the middle for the screen mouse and soo on.
<br>
<br>
<br>
<br>
 <!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <div class="numbertext">1 / 4</div>
    <img src="/assets/Images/DeskClipLeft.jpg" style="width:100%">
    <div class="text">Caption Text</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 4</div>
    <img src="/assets/Images/DeskClipLeft2.jpg" style="width:100%">
    <div class="text">Caption Two</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 4</div>
    <img src="/assets/Images/DeskClipRight.jpg" style="width:100%">
    <div class="text">Caption Three</div>
</div>
  <div class="mySlides fade">
    <div class="numbertext">4 / 4</div>
    <img src="/assets/Images/DeskClipLoose.jpg" style="width:100%">
    <div class="text">Caption Three</div>
</div>

  

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>




<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
</div> 

<style>


/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
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
    display:none;
  color: #000000;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
    display:none;
  color: #000000;
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

</style>

<script>

var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
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

(I remodeled them a bit after printing them out after learning from a few mistakes i made)

these clips make me able to suspend my cables behind my desk so that you cannot se them, and also lets me route them down each side where they can hide behind my computer on the right side, and my drawer unit on the left side.

If you have problems with wires sagging down and being visible from beneath the desk more middle clips kan be printed and used as a cable rest/suspender.

if you have a Linnom or a Gerton Desk From ikea you can download the 3d files for the clips right [*here*](https://www.thingiverse.com/thing:4737552). You could probably also pretty easily make edit the clips to work on your desk.