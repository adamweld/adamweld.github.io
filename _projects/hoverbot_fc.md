---
title: 'Hoverbot Flight Controller'
subtitle: 'A tiny, powerful quadcopter flight controller with LIDAR'
date: 2020-06-30 00:00:00
description: 'Hoverbot Flight Controller: a tiny, powerful quadcopter flight controller with LIDAR'
featured_image: '/images/electronics/fc_3d1.png'
category: 'electronics'
---

## Hoverbot Flight Controller Board
I am designing this multirotor flight controller PCB as a tightly integrated project for a next generation Hoverbot quadcopter. One of my most difficult boards thus far, I wanted to include some brand new sensors and design features while staying within tight size and weight constraints. It was thrilling to have full creative power over the entire electrical and mechanical design of this PCB, which is central to the new quadcopter design. The sensor placements define much of the mechanical design, while board mounting and vibration isolation limit and instruct the component placement on the electrical side.

Current specifications:

* 30 x 30mm four-layer PCB
* STM32F4 microcontroller @ 120MHz
* On-Screen-Display 
* 4x 1-3S Brushless ESCs
* STM VL53L1X LIDAR Altimiter
* Bosche 6-Axis IMU
* CC2500 2.4GHz Digital Transceiver
* 5.0V Buck/Boost and 3.3V Buck regulators

![](/images/electronics/fc_3d1.png)

![](/images/electronics/fc_3d3.png)

![](/images/electronics/fc_2d1.png)

For more information see [Hoverbot](/robotics).