---
layout: post
title: "VeryManyGames"
date: 2020-11-23
categories: [Flutter,App development,GraphicDesign,Marketing,Google play store, Android, IOS, SEO, Admob, Google ads, nodejs, docker]
image: /assets/Images/WhoMeLogo.svg
---
All the way back in december of last year. My girlfriend got a great idea for a drinking game. And i thought "hey, why not make that?" that drinking game idea turned into a small fake company called VeryManyGames. And a whole bunch of other, relatively futile exercises. 

<!--more-->

To be clear i never really though this project would go any where or make me any money. But i always just kinda hoped, and that hope really just motivated me an unreasonable amount (that and the fact that at the time, i really had nothing better to do).

You can go to the website i made for this app [*here*](https://verymanygames.com/)

# The Idea
The Idea all started in my girlfriends head, when she go tired og the same type of "truth or dare" drinking games that can and is only played to get drunk, and in the greater picture get pretty boring pretty quick.

The idea was, instead of guessing on the same randomly selected questions, the players of this game would answer a personal question, and then the game would be guessing who had answered what.

Now, i don't know or think this was an original idea, but none the less i was compeled to make it, as i was very bored at the time. ( also i wanted to learn flutter, and this seamed like a great start)

# The execution
So, How was the app made. Being only one person, and pretty much having ulimited time really helped the development process. mostly all of the flutter code was written 10 min after i had learned about it. And most of the code was written when i just kinda felt like it. My girlfriend did though chime in, and helped write the questions (of which there is about 150).

the app it self is (as previously mentioned ) written in flutter. Flutter is ( as descriped by their website ) "Google’s UI toolkit for building beautiful, natively compiled applications for mobile, web, and desktop from a single codebase. " this is nice, cause that meant i could make my app for both iphone and android, and i could do it all one man without needing a huge development team. When i started on this journey flutter did not yet support desktop, but that has since change. Overall this project was a really good fit for learning flutter, but also flutter just is a very flexible and amazing tool.
You can see the source code for the app [*here*]()

# The Design
The design of the app, was first made in [*figma*](https://www.figma.com/). a lovely free online design tool developed in rust and running in web assembly.(this isn't really important i just think it is cool). The design went through 3 iterations. The first iteration was design around the idea of a felt covered gambling table, as i wanted the game to have a tabletop vibe. this design was quickly scrapped because it was ugly, as you can se below.
![NO IMAGES](/assets/Images/WhoMeFirstLogoDesign.png)

my girlfriend then made a design, that i unfortunately cannot show, as she still uses such caveman technologies as paper, and it therefor was lost forever. i did whoever mix this design, with the new spankled neumorphism i saw popping up everywhere. And that was how the final design came to be.
# The Marketing
Now the easy part was done, the game was made. BuUUUuuUut. How do you then get people to download it and... like play it and stuff..... Well, the first step obviously was telling (and playing the game with) my friends.

The first obvious step ( to me at least). was creating a website. So i went and bought the domain VeryManyGames.com. a callback to the fake company name i had given google so i could upload my app. and then i stole a container on my dads docker server to host it.
Now, i could have hosted this website with nginx or apache, or any other regular old static website hoster. But because i had the genius idea of giving away free expansions question packs as a way for me to use 0 dollars on marketing, but still have something to draw people in. i went with a dockerised version of nodejs. 

Now, i still wasn't getting eny downloads from just having a website. So i started spreading the game across varius relevant subreddits hoping to lure people in with the free gift pack. That netted med a few downloads, but honestly not as many as i was hoping for. the next step for me was to try and search engine optimise my website so mre people would find it oranicly while looking for drinking games. i did a few A B test on the play store and even looked up some generic "how to get more downloads on the google play store" articles. most of them didn't seem to be much help though, and just suggested things like " add emojies to your app name to make it stand out". in the end the only thing that seemed to get my app to the number one spot when searching for it's own name was breaking 100+ downloads. i did this with the free 20$ us you get when signing up for a google ads account. it took approximately 2 weeks of me fiddling with the setting so that all my free money weren't going to indian click farms. in in the end it took about 2 week's more for googles ai thing ( i don't know how it works ) to figure out who liked my ads. i ended up having to put ind a little of my own money (about 20$ more). but in the end i got a little over 75 downloads in one day, and subsequently blew through the rest of my cash. i had created a few text ads, and also some image ad banners, but in the end it was this glorious masterpiece of a youtube ad that seem to net me the most downloads.

<iframe width="560" height="315" src="https://www.youtube.com/embed/iiJ7GEH-RDc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

i also made a bing advertising account just because they also gave you free money for signing up, but in the end i only got like 3 downloads from that. i don't know if that was a problem with me or bing ads.

# Conclusion

in conclusion the app could probably have done pretty well, had i just used a little more time (and money) advertising it to people. and had i kept developing it. i still live in a weird kind of hope that i will just magically blow up by it self, but that is probably not gonna happen. in the end i stopped working on it as i started in bootcamp in february, and the military didn't exactly leave a bunch of time for app development.

i did return to it after my bootcamp training. I made a second pack, and halfway developed a kahoot like function where people could answer separately from their own phone. and maybe i will release an update som time in the future. But for now i have got what i wanted out of this project (learning flutter and being less bored).
