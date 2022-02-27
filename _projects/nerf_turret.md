---
title: 'Gimballed Turret with Face Following'
permalink: /projects/nerf_turret/
excerpt_separator: <!--more-->
toc: true
share: false
related: false
comments: false
paginate: false
read_time: false
time_worked: "Jun 2020 - Sep 2020"
date: 2020-6-1
show_date: false
---

Developed two-axis gimballed stand with mounted NERF blaster. Used Raspberry Pi with OpenCV to detect facial features to shoot foam darts at target. Low-level motor control managed with Arduino.
<!--more-->

# Project Overview

Exploration of OpenCV, computer vision, serial communication, motor control, and facial detection.

# Implementation

* Stepper motor base allowing 360 degree rotation.
* Servo enabling ~45 degree vertical pivoting of blaster.
* Camera mounted on blaster, using OpenCV to detect faces and provide location.
* Basic scheduled bang-bang controller to direct motor movements.