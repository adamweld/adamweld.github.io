---
title: 'Power Regulation Board'
subtitle: 'Multiple voltage, high current output power regulation daughterboard for UAS'
date: 2030-06-30 00:00:00
description: 'Power Regulation Board: Multiple voltage, high current output power regulation daughterboard for UAS'
featured_image: '/images/electronics/reg_pic.jpg'
category: 'electronics'
---

## Power Regulation Daughterboard
This power regulation board was designed for my project team CUAir at school. It takes as input two LiPo batteries (a 2S autopilot and servo pack and a 6S general paylods pack), and a 28V ground supply. It outputs a number of different voltage rails to power all payloads in our unmanned aerial system. It also has a microcontroller to manually switch inputs and report if voltages are in range.

![](/images/electronics/reg_pic.jpg)

![](/images/electronics/reg_2d.jpg)

![](/images/electronics/reg_2d_2.jpg)

![](/images/electronics/reg_3d.jpg)

My mentor on the team challenged me to try to use only two copper layers for the design, and I was unable to refuse.

* Two Layer PCB, 40 x 60mm
* three-week design time

| Input Level   | Output Level  | Amperage|
| ------------- | --------------| -----   |
| Payload 6S    | 12V_KB        | 4A      |
| Payload 6S    | 5V_KB         | 5A      |
| Payload 6S    | 3V3_KB        | 2A      |
| Autopilot 2S  | 5V_AP         | 12A     |
