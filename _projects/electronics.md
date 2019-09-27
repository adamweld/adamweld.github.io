---
title: 'Electronics'
subtitle: 'PCB Design and Layout'
date: 2018-06-30 00:00:00
description:
featured_image: '/images/electronics/main.jpg'
categories: [electronics]
---

![](/images/electronics/main.jpg)

## Electronics

I've enjoyed working with electronics from a young age, and as a child had an insatiable desire to take apart old and broken devices in the hope of figuring out how they worked. By the time I was twelve I had trained all of my neighbors to let me take a look at their broken electronics before giving up on them, and knew of many of the treasures hidden inside inconspicuous beige enclosures - neodymium magnets and brushless motors from a frozen hard drive, laser diodes from a DVD player, high voltage generators inside a disposable camera flash.

What captivated me then, and continues to hold my attention now, is the process of turning an idea for a device into a finished product. I've learned the hard way that design for manufacture is a philosophy that must be maintained from the very start of project, not an optimization that can be slapped on at the end. Complex, highly integrated electrical and electromechanical projects are my bread and butter.

Below, you can see a few of my recent printed circuit board designs.

---

### Hoverbot Flight Controller Board
I designed this multirotor flight controller PCB as a tightly integrated project for a next generation Hoverbot quadcopter. One of my most difficult boards thus far, I wanted to include some brand new sensors and design features while staying within tight size and weight constraints. It was thrilling to have full creative power over the entire electrical and mechanical design of this product!

* 30 x 30mm four-layer PCB
* STM32F4 microcontroller @ 120MHz
* On-Screen-Display 
* 4x 1-3S Brushless ESCs
* STM VL53L1X LIDAR Altimiter
* Bosche 6-Axis IMU
* CC2500 2.4GHz Digital Transceiver
* 5.0V Buck/Boost and 3.3V Buck regulators

![](/images/electronics/fc_3d1.jpg)

![](/images/electronics/fc_3d3.jpg)

![](/images/electronics/fc_2d1.jpg)

For more information see [Hoverbot](/robotics).

### Hoverbot Design Verification Boards
I put together these PCBs to verify my schematic design and component selection for the above flight controller project. The first larger board helped me spot a few serious issues with the schematic and footprint library, such as the WS2812B LEDs having reversed pin polarity in the Altium content vault library. I also had bringup difficulties with the analog video OSD chip, and ended up redesigning for better voltage filtering to that IC.

![](/images/electronics/test_paste.jpg)

![](/images/electronics/test_place.jpg)


### Power Regulation Daughterboard
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


### Secret Bezos Board
I'm only able to share this work using the principle of safety by obscurity.

![](/images/electronics/gdb_3d.jpg)

![](/images/electronics/gdb_2d.jpg)
