<!--
---
#layout: post
#title: "Github Course"
#date: 2021-02-02
#categories:
#image: /assets/Images/Git-XKCDComic.png
---
-->

<!--more-->

# Why git
Many people find them selfs naturally questioning why there is no such thing as a google docs for programming. A nice online editor where we can all just write at the same time and cooperate that way. well, the simple answer is that it would be horrible to ever run and test your code. Imagine every time you try to run your code, somebody else somewhere has now introduced a new error somewhere else in the code and now it won't run, or maybe someone is in the middle of writing a function and then the code won't compile. This simply won't do. Luckily for us some very smart people who was trying to write a very nice operating system (linux) came up with a solution for us.
*comic stolen form xkcd*

## so what is git?
Git is a branching version control system. this means it keeps track of all the changes you make so that if you fuck something up you can roll back to a staple release. this also means it can use all the data it has on line changes, and with a little bit or your help sometimes, it can merge my changes with your changes and thereby allow us to collaborate on code.
<!-- expand on explanation-->
<br>
<br>
<br>
<br>




# Creating a repository
So to start git you have to create a repository, also commonly called a repo.
A repository is just a folder of files for git to keep track of.

this can be done with the command in the desired folder

``` cmd
git init
```

it can also be done on github.com by logging in and then pressing the "new" button and filling in the information. keep in mind you will have too clone this repository to use it. we will get in to how to do that later.
<br>
<br>
<!--Fix image text-->
<img src="/assets/Images/GitHubWebCreateRepo.png" align="left" width="50%" >
<img src="/assets/Images/GitHubWebCreateRepo2.png" align="left" width="50%" >
...
<br>
<br>
<br>
<br>
or it can be done with github desktop by pressing "create a new repository on your hard drive"
<br>
<br>
<img src="/assets/Images/GithubDesktopCreateRepo.png" align="left" width="100%" >

a git repository can be identified by the .git folder that stores all the information git needs.

# staging and committing

in order to do it's job and "control versions" git needs to know what changes you have made to your project so that you can roll back to the or discard them if they did not work. to do this you have to tell github (and in tern everyone you are working on the software with) what it is you have done.
you do this through staging and committing.

first you have to "stage" the files you want git to remember the changes in. you do this with the command
```
git add Insert file name
```
or
```
git add *
```
here the * just means you want to stage all the changes you have made, this will be the one you use most often

in github desktop this is just done with the simple check marks to the left of the window
<img src="/assets/Images/GithubStaging.png" align="left" width="100%" >

now you can add them to the list of changes by "commiting" them. this is done with the command

```
git commit -M"Message for your commit"
```
or in Desktop github it can simply be done by writing your commit message in the lower left corner and pressing commit
<img src="/assets/Images/GithubCommit.png" align="left" width="100%" >

# adding remote origin and pushing

# fixing merge conflicts

# Branching

# pull requests

Last but not least if you have any changes you want to make to this little "Tutorial" be that grammatical errors or better explanations you can add them by making a pull request. THATS RIGHT! PLOT TWIST THIS WHOOLE WEBSITE IS A REPOSITORY!!! you can view it [*here*](https://github.com/fred441a/fred441a.github.io)

# Dictionary / Refrence

## Repository (repo)
what a project is called in git. refers to a folder git is keeping track of
``` cmd
git init
```

## staging
This is when you tell git which changes you want to commit and which you don't

```
git add INSER FILENAME OR *
```

## Commit
a "milestone" on your branch or simply a group of changes that you have chosen to give a name / description.

```
git commit -M"The name / desciption of your commit"
```


