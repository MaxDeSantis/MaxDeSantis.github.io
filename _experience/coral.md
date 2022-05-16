---
title: 'Controls, Robotics and Automation Lab (CoRAL)'
permalink: /experience/coral/
excerpt_separator: <!--more-->
toc: true
share: false
related: false
comments: false
paginate: false
read_time: false
job_title: "Undergraduate Research Assistant"
time_worked: "Aug 2021 - Present"
date: 2021-12-24
show_date: false
---

Paid and volunteer research and contributions to a number of projects including: support for spatiotemporally varying wind in Microsoft Airsim; wind-aware piloting interfaces for unmanned drones in QGroundControl; the ongoing development of an autonomous ground vehicle.
<!--more-->

# Spatiotemporal Wind Simulation and Wind-Aware Display
I began a paid position with CoRAL in August 2021, where I work with Dr. He Bai and PhD candidate Asma Tabassum. Our group is investigating the development of displays that communicate wind velocity acting on low-altitude aerial vehicles. Towards that effort, I introduced support for spatiotemporally varying wind to [Microsoft Airsim](https://github.com/microsoft/AirSim/), a high-fidelity dynamic simulator built in Unreal Engine. The wind used can be generated using computational fluid dynamics software, allowing for more accurate (and faster) results than a real-time computation. This work was based off of a similar feature in in the [RotorS](https://github.com/ethz-asl/rotors_simulator) simulator.

Furthermore, I implemented several wind-aware displays into QGroundControl (QGC), a popular FOSS mission planner and ground station for unmanned pilots. Communication between Airsim, QGC, and the flight stack is done through Mavlink, an established and popular protocol. This involved minor modifications to QGC's source code and the PX4 flight stack. I am presently working on developing realistic urban simulation environment and wind-optimal trajectory generation and recommendation.


# Autonomous Golf Cart
I began working with Dr. He Bai at CoRAL during my first semester. While there I was mentored by two other undergraduates and began working on replacing the low-level control system for our Autonomous Golf Cart. Myself and another undergraduate developed controls on an embedded STM32 board to handle braking, steering, and wheel speed control. I went on to assist with two senior capstone projects on the cart as we advanced it towards SAE Level 3 autonomy.
