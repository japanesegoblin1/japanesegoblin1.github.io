---
layout: post
title: UTME HERO – Integration of a Wearable Haptic Device with a VR/AR system for the purpose of teaching thoracostomies
description:  Completely rebuilt and improved upon A Wearable Haptic Interface Combining Kinesthetic and Tactile Sensations for 6 DOF Haptic Guidance with the purpose of improving teaching thoracostomies by printing the wearable mesh with PETG and hand building a custom PCB, as well as Expanded the initial implementation integrating the device with Ultraleap, ROS, Unity, and Meta Quest. 
skills: 
- Arduino
- PCB Building/Soldering
- CAD
- 3D Printing
- Rapid Iteration
- Programming
- Unity
- ROS
- Ultraleap Integration
- VR Integration
main-image: /hero2.jpg
---

---
#For those who don't want to read the whole blog post about this project, here is the TL;DR explaination of this project
The project essentially sought to try to make the process of learning how to do a thoracostmy easier.
To summarize the issue, thoracostomies are a type of surgery, among other things, have the combined trouble of being low frequency and high failure rate. Studies (hopefully linked here soon) were done as to why, and it basically amounted to the procedure being very dependent on intuition, which is built by experience. Since the procedure itself is fairly uncommon, doctors have little access to good practice.

The way we wanted to approach it, from a high level, was to create a simulation that has live haptic feedback when something goes wrong in the simulated procedure. Generally speaking this will be incorrect tube insertion depth (big one), and bumping into objects like ribs or something like that in the body (smaller but still big issue). One big thing with the feedback is that there is this sort of "popping" (gross I know) when the tube is inserted correctly, and that especially is hard to understand when you don't know what you are looking for.

# The big blog post is currently under construction. I am trying to get better images and documentation of everything at the moment.
If you have any questions about this project, please contact me at the bottom of the main page!

{% include image-gallery.html images="hero2.jpg" height="600" %} 

{% include youtube-video.html id="C44VwBty0CQ" autoplay= "false" width= "900px" %}

# Where to start?
## What is the goal of this project?
## What is a thoracostomy?
You can essentially break this project down into 3 main parts.
- The sleeve itself
- Electronics/motors/etc
- Software
