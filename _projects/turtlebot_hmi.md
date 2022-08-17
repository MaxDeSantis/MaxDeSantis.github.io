---
title: 'Point-and-Click Robot Interface'
permalink: /projects/turtlebot_hmi/
excerpt_separator: <!--more-->
toc: true
share: false
related: false
comments: false
paginate: false
read_time: false
time_worked: "Aug 2021 - Jun 2022"
date: 2021-8-01
show_date: false
skills: [ROS, Python, Javascript, 3D vision]
---

Mobile robot human-machine interface.

<!--more-->

# Project Overview

Human-machine interfaces can vary in many ways. Keyboards, mice, joysticks, voice control, and touchscreens are all be used in various situations to control robots. My objective was to create the simplest possible manual-control scheme wherein the user is prevented with the robot's view to "point and click" where to go. This view could be a direct camera view or a 2D representation of other data.

# Implementation

The interface was built as a webpage, using the ROS web-bridge package. The ROS web video server package is used to transfer a live video feed from the robot's perspective to the interface. The user can click anywhere on the provided image; an action server notifies a local control node of the click location. A stereo depth camera then provides the depth at the given point. Click location and depth are combined and transformed into the robot's local frame and used as its goal position. It navigates to the point and avoids obstacles however it sees fit, as that was not in the scope of the project.

The interface worked well in a simulation using a Turtlebot3. Integration on a hardware platform was begun, but has been postponed indefinitely. One caveat is the requirement of a depth camera or other depth-sensing hardware. A problem encountered was that there is no easy way to rotate the robot or guide it to locations behind it. This was solved with the introduction of two simple rotation buttons which make the robot spin in place; this maintains the simplicity but greatly enhances the functionality.

More information on my poster [here](/_paperspresentations/2022_poster_urs.md).