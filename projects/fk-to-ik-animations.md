---
layout: project
type: project
image: images/iK.png
title: Fk to Ik Animations
permalink: projects/fkToIk
date: 2018-12-01
labels:
  - IK animations
  - UE4
summary: A system to translate traditional FK animations into IK animation targets.
---

<img class="ui medium right floated rounded image" src="/images/iK.png">

A program created in the game engine UE4 for my senior independent project in highschool. It takes in animations in the standard Forward kinematic format and saves positions that can be used to run IK animations. Animations using forward kinematics specify angles at specific times for each joint. So when playing back the animation, the computer poses the model with each joint having that set value. IK animations, on the other hand, gives a position for the joint at a specific time. And when the computer plays back the animation gradient descent is used to figure out the angles the joints should be at to match the target positions. The advantage of having IK animations is you can overlay physics simulations over the animation, something that wouldn't be possible if the animation was just saved in FK form. Another possibility is to let the user control individual appendages like seen in the image where the arm is being controlled with the trackpad.

