---
layout: project
type: project
image: images/cel4.png
title: Firewatch Celshader rebuilt in UE4
permalink: projects/micromouse
date: 2018-04-01
labels:
  - UE4
  - Graphics Programing
summary: Recreated the distance coloring shader used in the game Firewatch.
---

<img class="ui medium right floated rounded image" src="/images/cel1.png">
<img class="ui medium right floated rounded image" src="/images/cel2.png">
<img class="ui medium right floated rounded image" src="/images/cel3.png">
<img class="ui medium right floated rounded image" src="/images/cel4.png">

This program was created for the AP comp principals exam (although they didn't really know what it was 😅).
The shader uses a 100x1 image as an input and adjusts the color of the scene based on the image. The shader considers every object's distance from the camera (the player) and will choose a corresponding color along the pixel strip based on the distance. The shader then adjusts the color of the object to be closer to that color. The overall effect is a kind of gradient fog effect where objects are tainted with different colors based on their distance away from you. A shader similar to this was used in the 2016 game Firewatch.
