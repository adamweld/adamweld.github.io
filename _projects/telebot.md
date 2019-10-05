---
title: 'TeleBot'
subtitle: 'Raspberry Pi Telepresence Robot'
date: 2026-06-30 00:00:00
description: 'TeleBot: Raspberry Pi Telepresence Robot'
featured_image: '/images/robotics/telebot_wide.jpg'
category: robotics
---

This was a really fun final project for [Joe Skovira's Embedded Operating Systems class](http://skovira.ece.cornell.edu/ece5725/), completed with Ryan Hornung.

Our project report webpage can be found [here](https://courses.ece.cornell.edu/ece5990/ECE5725_Spring2018_Projects/rmh286_aw698/index.html).

![](/images/robotics/telebot_wide.jpg)

The final complete design. Not much left from the original RC car.

![](/images/robotics/telebot_1.jpg)

We began by stripping the car down, and found that the included electronics were next to useless. The steering system only provided full lock steering with no granularity, and there was no simple way to control the main motor speed controller without using the wireless remote. So, we stripped everything out and started from scratch.

![](/images/robotics/telebot_2.jpg)

An initial motor controller in place, which ended up not being powerful enough for the main motor. In the end we used this controller to power the siren.

![](/images/robotics/telebot_servo.jpg)

![](/images/robotics/telebot_3.jpg)

Here I've carefully replaced the steering mechanism with a real servo motor. A siren soldering practice kit that we found behind a file cabinet in the lab also lends some flair and downforce. You can also see a USB speaker and microphone mounted to the front.

![](/images/robotics/telebot_4.jpg)

The RPi, screen, wireless dongle, and battery pack mount neatly to the car with velcro. Just a bit of soldering needed to connect the GPIO output to the car's port.

![](/images/robotics/telebot_close.jpg)

Zip-ties come to our aid in mounting the camera.

![](/images/robotics/telebot_wide.jpg)

Project Demo:
<iframe width="640" height="360" src="https://www.youtube.com/embed/dGhWkqhyawY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
