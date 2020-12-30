---
layout: post
title: "This Website"
Date: 2020-11-21
categories: [HTML, CSS, Web, Jekyll Github, GraphicDesign]
---
In this post i will be discussion the creation of this very website, and the stuff i think is fun and interesting. And things i learned along the way of making it.
<!--more-->

you can find the source code for it [*here*](https://github.com/fred441a/fred441a.github.io)

To start of with i made a design on paper on how i would like my website to look. It's a little rough. but it is just at sketch 
<img src="/assets/Images/FirstDraftWebsite.jpg" style="width: 100%" >

i wanted a personal website that kind of looked like i had drawn it in hand (a bad idea given how i am horrible at drawing)

# Making my own font:
<img src="/assets/Images/Calligraphr-Template.png" align="right" width="200" >
To do that i would need a font of my own handwriting, so that i would not have to write every paragraph on my website by hand.
to do this i used a website called [*Calligraphr*](https://www.calligraphr.com/en/).

The website itself is pretty straight forward to use, and there is a step by step guide when you log in. simply put the website generates a template for you with all the character you would want in your font (limited to 75 in the free version). you are then supposed to print it out, draw the character on it, and then scan it back in and upload it to the website. i am too lazy for that though, and just used my brothers drawing tablet and an image editor ([*Gimp*](https://www.gimp.org/)) to draw my characters.

One problem though. I wanted more than 75 characters, but i am also too cheap to pay for the pro version. Easy fix. just "Build" and download your font two times with different characters. i now have two fonts 1 with 75 characters and another with the rest of the characters. i then used a program called fontforge to simply merge the two fonts into 1 file ( and convert it in to a .woff)
i call this magnificent masterpiece "FredsFont".

You can download it and use it for whatever you want right [*here*](/assets/Style/FredsFont.woff)

i dont know what you would want it for... but hey whatever, it's yours.

# Inkscape and a bit of fun drawing stuff:

Now for the assets of the website, i just needed a hand drawn box for my main page, and also some small social media icons for the footer. to make these i used the previously mentioned drawing tablet, and one of my favorite free and open source programs [*inkscape*](https://inkscape.org/). 

Now, i could have used Gimp here again. However i am a sucker for quality, and nothing is higher resolution than vector graphics.
For the box i obviosly just drew a box. For the icon though i just downloaded the icons from the internet, and then traced them. (except for the mail... which i just drew freehand) 

# The power of jekyll and github pages:
Now comes the real cool stuff (in my opinion). i had planned to use GitHub pages from the start of this project. for those out of the know github pages are simply pages hosted in a github repository, which github then provides a smansy pansy url for. you can have one for individual pages of for your profile. If you are interested in them, you can read more about them [*here*](https://pages.github.com/).

Well, it was when looking at this very website that i noticed they supported something called Jekyll. I did not now what Jekyll was at the time, but it looked cool so i looked into it. Turns out Jekyll is a "static site generator". What that means is that Jekyll is a program that takes the text that you write and puts it in to a predefined theme. meaning ones you are done making your main HTML files you can just use jekyll cram all the text you wrote in to those html files, and keep track of all the individual pages. it is very simply, but at the same time insanely powerful and flexible. i have no doubt that building my site in jekyll from the beginning will save me a bunch of time, while still also letting me do what i want with the site(unlike many blogging systems and site builders). Of course i jumped right in head first and design my own theme for jekyll from the ground up.

you can see the source code for the site [*here*](https://github.com/fred441a/fred441a.github.io)

and you can read more about jekyll [*here*](https://jekyllrb.com/)
# Css flexbox:
It's has probably been way too long since i have done front end html web development. or maybe i was just not so observant back then i did. but some time around 2013 i started to hear about this css flexbox thing, but i never really used it. i just kinda stuck to my old bootstrap and weird js built ind sizing solutions. and i just wanted to say. im sorry css flexbox, i don't know why i didn't use you. Whether it was neglect or just pure ignorance. but i used you now.... and boy do i like you.
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTI3MTY1NDAyXX0=
-->