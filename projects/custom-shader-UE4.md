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
The shader uses a 100x1 image as an input and adjusts the color of the scene based on the image. The shader considers every object's distance from the camera (the player) and will choose a corresponding color along the pixel strip based on the distance. The shader then adjusts the color of the object to be closer to that color. 

The system is made with a hybrid of blueprints and HLSL (it's been awhile so I don't actually remember what did what). It was a good experience trying to figure out how to recreate someting with tools I've never touched before in a very small time frame (a couple spare hours between homework and judo practices). I tend to find I learn alot more if I try to puzzle through and do alot of the learning on my own so this was another good opportunity to practice that process.

The overall effect is a kind of gradient fog effect where objects are tainted with different colors based on their distance away from you. A shader similar to this was used in the 2016 game Firewatch. This helps create depth in scenes and gives the renders a certain style. It also allows you to easily change the color pallate of the world by just swapping what input strip you feed into the program (can be controlled with a switch statement based on a variable). 
