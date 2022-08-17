---
title: 'Vehicle for Emergency Location and Assistance (VELA)'
permalink: /projects/vela/
excerpt_separator: <!--more-->
toc: true
share: false
related: false
comments: false
paginate: false
read_time: false
job_title: "Electrical and Controls Lead"
time_worked: "Oct 2020 - Jun 2021"
date: 2021-6-24
show_date: false
skills: [ROS, C++, Pixhawk, composite materials, power distribution, antenna design and analysis]
---

Development of autonomous search and rescue vehicle to locate and deliver supplies to stranded astronauts after emergency egress from capsule. Completed for the NASA Micro-g design competition.
<!--more-->

# Intro

Each year NASA prepares a list of challenges for which they want undergraduates to design solutions. These challenges can range from mechanical tool designs such as a regolith sampler to equipment improvements such as EVA quick detach systems. The solutions are then tested in NASA's Neutral Buoyancy Lab (NBL). The Surface Autonomous Vehicle for Emergency Rescue (SAVER) challenge required the design and construction of an autonomous search and rescue vehicle. SAVER was intended for use as a force-multiplier in the scenario where one or more astronauts are separated from their capsule after splashdown. Its goal is to deliver necessary survival supplies to said astronauts while they await retrieval.

This project involved a team of undergraduates at OSU comprising of myself, Collin Thornton, Lucas Hudson, Kelly Lewis, and Ryan Turner.

# Problem

1. Seek out astronaut autonomously using 121.5 MHz distress beacon.

2. Carry water, radio, life jacket, ANGEL beacon and first aid kit.

3. Survive deployment by Group 1/2 drone into maritime environment - 10-15ft drop expected.

# Solution

Our solution was a monohull vessel constructed out of fiberglass. We attempted thermoforming, but found it to be less reliable with the equipment we had available. Two separated, waterproof electronics boxes are stowed in the hull. One performs power regulation and distribution duties. Other box contains computation electronics - Raspberry Pi 4B as main computer and custom PCB for homing.

A waterproof container fits inside a recessed interior, held inside by velcroed bungee straps. This holds the survival supplies. A forward facing camera intended for telemetry and obstacle avoidance was installed as well. Custom-built antennas are installed as two pairs of monopoles - one pair along each axis. These are meant to be used for tracking the 121.5 MHz distress signal.

# My Contribution

* Handled computer integration into vehicle including the ROS network, WiFi remote access, on-board ADC, relay control, camera support, etc.
* Designed and constructed power distribution system.
* Managed antenna construction, installation, and testing.
* Assisted in development of homing PCB.