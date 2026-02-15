---
layout: post
title: UTME HERO – Integration of a Wearable Haptic Device with a VR/AR system for the purpose of teaching thoracostomies
description:  Completely rebuilt and improved upon A Wearable Haptic Interface Combining Kinesthetic and Tactile Sensations for 6 DOF Haptic Guidance with the purpose of improving teaching thoracostomies by printing the wearable mesh with PETG and hand building a custom PCB, as well as Expanded the initial implementation integrating the device with ROS, Unity, and a Meta Quest. 
skills: 
- Arduino
- PCB Building/Soldering
- CAD
- 3D Printing
- Rapid Iteration
- Programming
- Unity
- ROS
- VR Integration
main-image: /hero2.jpg
---

---
# Presented at the IEEE Haptics Symposium!! Yay!!!

# For those who don't want to read the whole blog post about this project, here is the TL;DR explaination of this project

The project essentially sought to try to make the process of learning how to do a thoracostmy easier.
To summarize the issue, thoracostomies are a type of surgery that, among other things, have the combined trouble of being low frequency and high failure rate. Studies (hopefully linked here soon) were done as to why, and it basically amounted to the procedure being very dependent on intuition, which is built by experience. Since the procedure itself is fairly uncommon, doctors have little access to good practice.

The way we wanted to approach it, from a high level, was to create a simulation that has live haptic feedback when something goes wrong in the simulated procedure. Generally speaking this will be incorrect tube insertion depth (big one), and bumping into objects like ribs or something like that in the body (smaller but still big issue). One big thing with the feedback is that there is this sort of "popping" (gross I know) when the tube is inserted correctly, and that especially is hard to understand when you don't know what you are looking for.

At a lower level, you can break our solution to this problem into 3 parts
- Sleeve
- Electronics
- Software

For the sleeve, we based our design from our predecessor, Bharat Mathur. We made a sleeve that was able to give haptic feedback in 6 DOF, while hopefully not being too cumbersome <br>
Electronics were completely redone, basically just header pins in a PCB that had to be hand soldered (pain in the ***), with it all eventually sitting on top of an Arduino MEGA <br>
Software was the interesting part, there were many subparts to this breaking down into:
- Simulated Environment
- Haptic Rendering (Hand Tracking included)
- ROS

Not gonna bother explaining this too much because I have rambled enough in a TL;DR. If you got this far, thank you for reading! I will leave you will video of this in action. Here, you can (hopefully) see the sleeve and the VR environment working! <br>
{% include youtube-video.html id="HykyClSQoaA" autoplay= "false" width= "1200px" %}

# The big blog post is currently under construction. I am trying to get better images and documentation of everything at the moment.
If you have any questions about this project, please contact me at the bottom of the main page!

{% include image-gallery.html images="hero2.jpg" height="600" %} 

{% include youtube-video.html id="C44VwBty0CQ" autoplay= "false" width= "900px" %}

# Where to start?

Generally speaking, training for emergency skills, like placing a chest tube (thoracostomy), takes many forms including demonstrations on cadavers, live animals, or live patients, as well as task trainers and VR simulators. For a thoracostomy, a tube is inserted into the pleural sapce with a clamp for the purpose of removing things like blood/air/fluid from a patient's chest cavity.


## What is the goal of this project?

Basically, we hope to create a system that very closely simulates a real surgery, while also having a "training wheels" type of situation so that the trainee isn't constantly under trial by fire. We hope to tackle the many challenges that come with this, but at a lower level, we hope to simualte and better train a more accurate and controlled insertion. What comes with this is the trainee recognizing and reacting adequely to the characteristic relief of pressure, described as a "popping" sensation that is often present when the instument punctures the pleural space. This generally indicates a correct procedure, but it is a little weird and most first timer's will not get it and will often go deeper despite the feeling. Without accurate physical feedback, VR simulations alone cannot help trainees internalize this intuition.

Generally, to induce this kind of physical experience, standard thoracostomy training is performed on chest tube trainers or cadavers. In either circumstance, the procedure's subject only has so many uses until a replacement is needed. Additionally, variables are generally unchangable, such as fat thickness, chest width, etc, without needing to change the entire subject, which could be expensive and not worth it.

## What is a thoracostomy?

## Sleeve Design

## Simulated Chest Trainer Environment

## Haptic Rendering

# User Study

## The Task

## Experimental Design

## Statistical Analysis Methods

# Results

# Discussion and Conclusion


