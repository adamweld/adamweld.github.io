---
title: 'Conference Telepresence Robot'
subtitle: 'Telepresence Robot for Local and Remote conferences'
date: 2022-06-30 00:00:00
description:
featured_image: '/images/mechatronics/conference_wide.jpg'
category: mechatronics
---

![](/images/mechatronics/conference_wide.jpg)

## Conference Telepresence Robot

This project for a Human Robot Interaction class at Cornell. For the second half of the semester, we were tasked with creating a robotic system that helps people work together. After a few rounds of ideation and rough cardboard prototypes and tests, we decided to focus on conferences and discussions. The main problems we wanted to address were turn-taking (local and remote conferences) and the lack of physical presence leading to poor attention towards a video conference attendant.

We conceptualized a robotic arm that would hold a video camera and screen, in our case a phone, and move around to focus on whoever was speaking in the room. In a local conference it would simply 'spotlight' the person speaking, in an effort to get everyone to pay careful attention and not butt into the discussion. We hoped that in a video conference, the physical precense would help the person on the other end of the video get more attention and allow them to focus more specifically on the individuals in the room when listening.

![](/images/mechatronics/conference_passive.jpg)

To start, I designed a passive version of the robot (with no motors, only friction joints) that would hold a phone and allow us to roughly test interactions. The design was created using carbon fiber tubes to reduce weight, as well as 3D printed and laser cut parts.

As research progressed, we needed to power the system's movement. After careful consideration of various types of motors, we decided to use simple but powerful brushless hobby servos. These gave good power to weight ratios, and delivered enough torque to be mounted directly in the middle of the joint without necessitating further gearing. We used a belt driven stepper motor on the bottom joint.

![](/images/mechatronics/conference_parts.jpg)

Having a few 3D printers in my basement allowed me and Eric (my housemate) to iterate very quickly on the mechanical design. Here's a tray of parts printed overnight. 

![](/images/mechatronics/conference_servo.jpg)

A better view of how the 'elbow' servo sits in the center of that joint.

I designed about half of the arm's 3D printed parts, and built a small scale 'voodoo doll' style controller with a miniature of the arm and a joystick for the end effector for the purposes of testing our hypothesis. I wrote firmware for an arm microcontroller to drive the stepper and servo motors in the arm, and smooth inputs for reduced jerk in motion. 

![](/images/mechatronics/conference_c2.jpg)

![](/images/mechatronics/conference_controller.jpg)
