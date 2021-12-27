---
title: 'Medical Oxygen Tank Timer'
permalink: /projects/oxygen_tank/
excerpt_separator: <!--more-->
toc: true
share: false
related: false
comments: false
paginate: false
read_time: false
job_title: "Project and Electrical Lead"
time_worked: "Aug 2018 - Jun 2019"
date: 2019-6-24
show_date: false
---

Real-time depletion timer for medical oxygen tanks commonly used by COPD patients. Addresses shortcomings of common timing methods with a variety of audiovisual indicators. Senior high school capstone project. 
<!--more-->

# Intro

Those suffering from lung diseases are often prescribed supplemental oxygen to make up for their lungs' inability to absorb sufficient oxygen. Treatment can come in a variety of forms; the mobile medical oxygen tank (familiar silver and green cylinder) and the portable oxygen concentrator are most common. We saught to address a problem faced by users of oxygen cylinders - patients cannot easily and reliably determine how long they can continue to use a cylinder before its depletion. One popular method is a two-axis chart comparing flow rate and cylinder pressure. This has shortcomings, as patients often suffer from declining eyesight, memory, or comprehension, and therefore struggle to accurately read or understand their chart. Furthermore, there has been at least one incident of a patient running out of oxygen in a hospital setting while being unable to speak or ask for helpful. (ADD CITATION)

This project was completed by a team of myself, Lucas Hudson, and Hayden Herzberger.

# Problem

1. Estimate how long a pressurized oxygen cylinder can be used at a given flow rate and pressure.

2. Display this information to the user in a straightforward manner.

3. Provide a variety of 

# Solution

We designed a modification for pressurized cylinders that attaches between the cylinder opening and post valve. This attachment has a pressure transducer that feeds pressure measurements into an attached microcontroller. The microcontroller uses pressure measurements and a known flow rate to estimate time remaining using regression. The estimation is then displayed on an attached screen, wirelessly transmitted to a mobile display, and broadcast to a locally hosted website. Furthermore, warnings using flashing LEDs and buzzers were introduced for set time threshholds.

We demonstrated our solution to professional engineers, healthcare workers, emergency responders, and the community. Positive reception from engineers and emergency services led us to pursue a United States utility patent, although our interests changed after graduation and we stopped our efforts.

# My Contribution

* Developed microcontroller measurement, display, wireless communication, warning, and estimation code.
* Managed testing, data gathering, documentation, and project deadlines.
* Core contributor to all aspects of design, implementation, and presentation.