---
title: 'Mechatronics'
subtitle: 'Actuators and Controls'
date: 2018-06-30 00:00:00
description:
featured_image: '/images/mechatronics/main.jpg'
categories: [mechatronics]
---

![](/images/mechatronics/main.jpg)

## Mechatronics
What's cooler that the collision of all of my favorite fields: electrical and mechanical design, sensors and actuators, and real time controls? 

Just about nothing, in my opinion.

### Stewart Platform
This three degree-of-freedom stewart platform, named "Stewy", was a final project built for a microcontrollers class. I took care of component selection, mechanical design, and the algorithm that controlled the stepper motors.

The platform was set up to mirror the attitude of a goat-shaped controller. The controller doubled as a mascot for our team, which we had previously dubbed the [microgoats](https://microgoats.life).

![](/images/mechatronics/stewy_close.jpg)

<iframe width="640" height="360" src="https://www.youtube.com/embed/LP0lPBt2ntQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Click [here](https://hackaday.com/2017/12/27/balance-like-a-mountain-goat-on-this-simple-stewart-platform/) for Hackaday.com coverage.


### Conference Telepresence Robot
This project for a Human Robot Interaction class is designed to give people on the sharp end of a telepresence video call, a bit more presence in the room. The end effector holds a phone, and the arm has five degrees of freedom to follow a converesation around the room and display emotion. 

I designed about half of the arm's 3D printed parts, and built a small scale 'voodoo doll' style controller with a miniature of the arm and a joystick for the end effector for the purposes of testing our hypothesis. I wrote firmware for an arm microcontroller to drive the stepper and servo motors in the arm, and smooth inputs for reduced jerk in motion. 

![](/images/mechatronics/conference_wide.jpg)

![](/images/mechatronics/conference_controller.jpg)


### Piezoelectric EM Microscope stage
One of my first hardware design engineering projects, but one that I am still very proud of. Working at desktop electron microscope company [Project Voxa](http://voxa.co/), I was tasked with working on a four-axis stage to move the sample around under the EM beam.

![](/images/mechatronics/voxa_office.jpg)

Because any kind of magnetic field will distort the microscope image, there are only a few types of motor that work in such a system. The most popular option is a piezoelectric motor, which I was tasked with prototyping as well as linear motion structure of the stage.

![](/images/mechatronics/voxa_piezo.jpg)

Here you can see a few of my rough prototypes of piezoelectric motors, and the final titanium wire-EDM machined flexure design for the final version. Piezoelectric motors work with a special type of ceramic crystal that lengthens and contracts a fraction of a percentage point when high voltages are applied across it. By using a saw-tooth wave and careful amounts of friction between the actuated end of the crystal and a plate, we can achieve linear motion by moving between static and dynamic friction.

![](/images/mechatronics/voxa_stage_wide.jpg)

![](/images/mechatronics/voxa_stage_close.jpg)

The motors fit into every axis of the stage in small cut outs.