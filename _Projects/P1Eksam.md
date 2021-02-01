---
layout: post
title: "First Semester Project"
date: 2021-02-01
categories: [ESP-32, Espressif, Embedded, Electronics, Problem Based Learning(PBL)]
image: /assets/Images/P1EksamensProdukt.jpg
---
As the title refers too this is my first semester project. The product of which was a prototype that will adjust your volume according to ambient noise, and warn you of your impending hearing loss

<!--more-->
First of all i want to make it very clear that this project was done by a group of seven people, and that therefore, i cannot claim that this was all me. Second of all, i will mostly be talking about the product and not the hole problem analysis and idea part of this project (Which honestly was most of it). If you want that you can read the rapport we made by writing me and asking me nicely if i will send it too you.

# the Problem / idea
The Problem we chose as a group was the rise in hearing loss due to personal audioplayers (mostly smartphones).
The best idea we came up with was some sort of integrated software solution in your phone that would essentially measure your exposure to loudness and then warn you and turn down your volume when appropriate. however, i am studying to become an electronics engineer and this solution was mostly software. So the idea we went with was a device the sits between your phone and your earbuds. in the prototype we use bluetooth as an interface between the phone and the device and a jackstick as an interface between our device and the earbuds.

# Components (What is this)

<img src="/assets/Images/ComponentsdrawingP1.jpg" align="left" width="100%" >

The Device connects wirelessly to your phone via bluetooth, and then sends the sound from your phone to the DAC(Digital to analog converter) via I2S. the DAC is then connected to the jackstick. The microcontroler on the ESP-32 monitors the ambient noise through the mic and adjust the volumen accordingly. It also monitors the volume of the audio being send too the DAC and warns you with the yellow light if your music is too loud. if your music has been too loud for too long the device will also lower your volume to a safe level.

Here you can here the device adjusting the volume to fit some "artificial" ambient noise (me yelling) and then turning down the volume when it gets too high for too long. 

 <audio controls>
  <source src="/assets/AV/AdaprivLydControl3medrødlys.wav" type="audio/wav">
Your browser does not support the audio element.
</audio> 

<!--insert audio here -->

and here is a video of me showing of the visualization system by blowing into the microphone to raise the volume.


 <video width="320" height="240" controls>
  <source src="/assets/AV/P1EksamenVideo1.mp4" type="video/mp4">
Your browser does not support the video tag.
</video> 


 <video width="320" height="240" controls>
  <source src="/assets/AV/P1EksamenVideo2.mp4" type="video/mp4">
Your browser does not support the video tag.
</video> 
<!-- insert video -->

you can read the code used for this [*HERE*](https://github.com/fred441a/LydeksponeringskontrolP1)
falthough i will admit it is kinda bad code. for instance all of the values for volume are complete guesswork as we could not calibrate and measure those correctly do too the audiolab being closed cause of covid-19. and the volume control technically just worsening the quality of the digital signal to turn down the audio. where in reality we probably should have used an external audio amp.