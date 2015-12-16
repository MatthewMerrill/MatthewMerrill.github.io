---
layout: post
title:  "PiPlotter - Humble Beginnings"
description: Beginning the project
sourcecode: 
  -
    title: PiPlotter-IO
    url: https://github.com/MatthewMerrill/PiPlotter-IO
  -
    title: PiPlotter-Server
    url: https://github.com/MatthewMerrill/PiPlotter-Server
  -
    title: PiPlotter-Android
    url: https://github.com/MatthewMerrill/PiPlotter-Android
date:   2015-12-16 2:00:00 -0800
categories: raspberrypi
---

<section id="main-content">
<h3>This semester...</h3>

Returning from winter break in my junior year of high school, my Physics teacher Mr. Wright made an annoucement:
<q>This semester, each of you will be presenting projects in the
<a href="http://www.folsomtelegraph.com/article/students-apply-skills-engineering-challenge"> 2014 Folsom Engineering Challenge</a>.
By February, have a project in mind or pick one from the project lottery.</q>

Because of my familiarity with building Java applications, I decided a Raspberry Pi project was the way to go. But what could I build?

<div>
<div id="youtube" style="float:right">
    <h5>Example XY-Plotter by "MakeBlock"</h5>
    {% include youtube-frame.html video='gTH3VjvCfpA' small=true %}
    </div>
<div id="text">
<h3>Tic-Tac-Toe?</h3>
Perhaps a robot to play tic-tac-toe against a human? This got me thinking. How could I move an arm along X and Y axes? After a little web surfing, I came across something called a "pen plotter". A pen plotter is similar to a printer, but traces a pen along its path instead of placing dots of ink row-by-row. Pen plotters allow for real-world applications of scalable graphics and quite graceful to watch.</div>
</div>

<div>
<div id="youtube" style="float:right">
    <h5><a href="http://ytai-mer.blogspot.com/">Ytai Ben-Tsvi</a>'s Inspirational V-Plotter</h5>
    {% include youtube-frame.html video='5v_nz6qzoZ4' small=true %}
    </div>
  <div id="text">
    <h3>Hanging around</h3>
    Not too long after researching pen plotters, I found the holy grail of high school Raspberry Pi projects - the "Hanging" V-Plotter.
    V-Plotters have the same goal as their cartesian cousins, but accomplish this task in a more complicated fashion.
    A pen rig hangs from two cables, and can push itself away from the vertical drawing board to temporarily stop drawing.
    The length of the two cables can be manipulated to triangulate to any point between and below the anchor points.
  </div>
</div>

<br>
<h2>Now I had a game plan!</h2>
{% include youtube-frame.html video='aZNT5mxjSRw' %}

</section>