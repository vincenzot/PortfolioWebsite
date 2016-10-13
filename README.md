# Portfolio Website - Udacity Nanodegree Project 2
A basic portfolio Website where users can view your featured work.

#Instructions
1. Download this repository;
2. You can edit the **index.html** to add your name, edit avatar and change project titles and links;

#Change the name
1. Open **index.html** file with a text editor and change this string
```
<h1 class="title-super text-thin"><p id="name">Vincenzo Tartaglia</p></h1>
```
```
<h1 class="title-super text-thin"><p id="name">Your Name</p></h1>
```
2. You can also edit the job written under the name (replace "Full Stack Web Developer" with your desired one):
```
<h4><p id="job">Full Stack Web Developer</p></h4>
```
#Change the avatar
1. Open **index.html** file with a text editor and change the src url in this string
```
<img class="title-logo" src="img/avatar1.jpg" height="100px" width="100px" alt="Portfolio Logo" />
```
2. You can use a local picture or paste an URL.

#Change the topbar picture
1. Open **index.html** file with a text editor and change the src url in this string
```
<img class="img-responsive main_picture" height="350px" width="1140px" src="img/topbar.jpg"/>
```
2. You can use a local picture or paste an URL.

#Edit featured work
1. Open **index.html** file with a text editor and find these strings (you'll find one for every work):
```
<div class="col-md-4 col-xs-12 col-sm-6">
					<a><img class="img-responsive pictures" src="https://placehold.it/555x300" /></a>
					<h3 class="text-uppercase">Appify</h3>
					<p class="url"><a target="_blank" href="#">https://github.com/appify</a></p>
				</div>
```
2. You can add your own works or edit existings, in the second case you need to change the following attributes:
```
<div class="col-md-4 col-xs-12 col-sm-6">
					<a><img class="img-responsive pictures" src="YOUR THUMB URL" /></a>
					<h3 class="text-uppercase">FEATURED WORK NAME</h3>
					<p class="url"><a target="_blank" href="FEATURED WORK URL">FEATURED WORK URL or A SIMPLE TEXT/DESCRIPTION</a></p>
				</div>
```
# Creator

**Vincenzo Tartaglia**

  - http://github.com/vincenzot
  - https://it.linkedin.com/in/vincenzo-tartaglia-33474a111
  - http://stackoverflow.com/users/5861977/vincenzo-tartaglia
