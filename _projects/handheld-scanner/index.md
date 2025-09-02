---
layout: post
title: Handheld Scanner 
description:  Designing a handheld scanner with LiDAR and camera for accurate 3D mapping and data acquisition
skills: 
  - PTP, NTP Time synchronization
  - GPS + PPS
  - ROS
  - UI/UX Design

main-image: /HH_expanded.png
---
## Timeline: 10 weeks 
---

## Goals: 
We aimed to create a transportable device that could run SLAM. The device would have a GPS for true clock and location tracking and use a NVIDIA Jetson Orin Nano as its computing device.

--- 

## Prototypes
{% include image-gallery.html images="hh_transparent.png, hh.png" height="2000" carousel=true %} 
We improved on each design, making the physical design more compact and optimizing the software. The final prototype consists of a NVIDIA Jetson Orin, Livox AVIA and HIKRobot camera.

---

## Software Design
{% include image-gallery.html images="flowchart.jpg, rqt_graph.png" height="2000"%} 

Combining existing drivers and our own, we integrated all the components of the handheld scanner so that it could collect data, run SLAM, and display location accurately.

[Github Link](https://github.com/alimuratov/handheld_scanner)

---
## Results
The handheld scanner was succesfully deployed at the MTR, Hong Kong's rapid transit system for data collection. It is able to be powered through one battery and has a touch screen for easy interaction.
{% include image-gallery.html images="person_demo.png, isoside.png, isoleft.png, isofront.png, isoright.png" height="1000" carousel=true %} 

Demonstration of running slam from GUI
<iframe src="https://drive.google.com/file/d/1VFsc2WfmTnYCoBWCJ5vMzzHVuPBR6vmw/preview" width="480" height="270" allow="autoplay"></iframe>







