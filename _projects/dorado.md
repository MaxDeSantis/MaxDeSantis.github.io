---
title: 'Device for Open-water Research with Aerial Docking Operations (DORADO)'
permalink: /projects/dorado/
excerpt_separator: <!--more-->
toc: true
share: false
related: false
comments: false
paginate: false
read_time: false
job_title: "Control Systems Lead"
time_worked: "Aug 2021 - Present"
date: 2021-12-24
show_date: false
---

Project for the Mercury Robotics design team in coordination with the Unmanned Systems Research Institute (USRI) at Oklahoma State University. Design and construction of an autonomous pontoon-style boat with onboard quadrotor capable of landing/taking off from the boat. Initial motivation was to seek out the source of an algal bloom by following its gradient in a lake. 
<!--more-->

# Intro
The development of algal blooms can cause a number of problems for aquatic life. We are interested in locating the point of highest "concentration" of the algae.

This project is a multidisciplinary, extracurricular activity for Mercury Robotics. In that regard we are interested in pursuing technologies and skills most valuable to Mercury team members' development as engineers. Therefore some subsystems receive in-depth treatment while others use COTS components.

# Problem
1. Design aquatic vessel to follow the gradient of the algae's concentration by measuring some parameter continuously.
2. Implement method for quadrotor takeoff and landing.

# Solution
The initial design is to develop a pontoon-style vessel due to its stability and large overhead surface area for carrier operations. Electronics will be mounted inside an elevated, water resistant box in the center structure of the pontoon.

The overhead platform is to support autonomous takeoff and landing of a quadrotor. Preliminary investigations suggest an electromagnet-based mechanical latching mechanism for a set of legs on the drone. Fiducials on the deck will aid in landing operations. We leave the possibility open for some form of quadrotor charging system, likely through off-the-shelf inductive charging circuitry.


# My Contribution
* Development of custom STM32-based embedded board for power delivery system.
* Onboarding of first and second-year students unfamiliar with robotics, control systems, embedded systems, etc.