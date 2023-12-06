---
layout: default
title: "IEEE @ SBU"
nav_order: 4
has_children: false
permalink: /IEEE
---

# Institute of Electronics and Electrical Engineers at Stony Brook University
{: .no_toc}

## Table of Contents 
{: .no_toc}

1. TOC
{:toc}

## What is IEEE?

![The IEEE Logo]({{ site.baseurl }}/assets/images/IEEE/sbu-ieee-white-bg.png)

IEEE, or the Institute of Electronics and Electrical Engineers is a student-run professional organization that aims to form a community of electrical engineers and further the knowledge, outreach, and networks of all those involved.

## What did I do in IEEE?

As the secretary for IEEE in the 2023-2024 school year, I lead techncial workshops and planned social events for the general body. These technical events include the Soldering Workshop, OPS, and more. In addition, I completed normal secretary tasks such as minutes and communication with outside entities.

### Soldering Workshop

This Soldering Workshop is being run in collaboration with [Stony Brook Robotics Team (SBRT)](https://sbroboticsteam.com/) and [Stony Brook Solar Racing](https://sbusolarracing.weebly.com/).

For the Fall 2023 Soldering Workshop, I created and programmed an ATTiny261A to play Simon Says. Using Fusion360 and JLCPCB, I manufactured a PCB that students would learn to solder on. Ultimately, the goal was to provide students with a credit-card sized trinket that they could be proud of making. 

#### Creating the schematic

Fusion360 was used to develop the design shown below. 
![Screenshot of an electrical schematic.]({{ site.baseurl }}/assets/images/IEEE/solderingSchematic.png)
*A Fusion360 screenshot showing the schematics of a PCB*

![Screenshot of an 2d schematic.]({{ site.baseurl }}/assets/images/IEEE/2dpcb.png)
*A Fusion360 screenshot showing the 2d board layout*

All chosen compoents are THT (Through Hole Technology) components for this Introduction to Soldering Workshop. A simple low-pass hardware debounce was used to increase the variety of components to solder. 
Components were also chosen to minimize cost: each student's project costs $4.81.

#### BOM
- [ATTiny261A](https://www.digikey.com/en/products/detail/microchip-technology/ATTINY261A-PU/1914698)
- [CR2032 Battery Holder](https://www.digikey.com/en/products/detail/keystone-electronics/3035/5872907)
- [0.1uF Capacitor](https://www.digikey.com/en/products/detail/kemet/C320C104K5R5TA7317/6562447)
- [LEDs](https://www.amazon.com/Emitting-Assortment-Voltage-Diffused-Indicator/dp/B07N2H23DC)
- [220Ω Resistor](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/CF18JT220R/1741639)
- [1kΩ Resistor](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/CF14JT1K00/1741314)
- [10kΩ Resistor](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/CF14JT1K00/1741314)
- [1825910-6 THT Buttons](https://www.digikey.com/en/products/detail/te-connectivity-alcoswitch-switches/1825910-6/1632536)
- [1825232-1 Slide Switch](https://www.digikey.com/en/products/detail/te-connectivity-alcoswitch-switches/1825232-1/4021554)
- [CR2032 Battery](https://www.amazon.com/LiCB-CR2032-Lithium-Battery-10-Pack/dp/B071D4DKTZ)

#### Prototyping and Programming

The PCB was manufactured using [JLCPCB](https://jlcpcb.com/).

![Screenshot of an 3d schematic.]({{ site.baseurl }}/assets/images/IEEE/3dpcb.png)
*A Fusion360 screenshot showing the 3d board layout*

Using AVRDUDE, AVR-GCC, and a makefile, I coded the game Simon Says for students to upload once they have finished programming. The github repo is here: [Soldering Workshop](https://github.com/Kyleh2420/IEEESolderingWorkshop). The code used both the ADC and the onboard TCA triggered on user input to enhance randomness. 

#### Running the Workshop

The official workshop lasted over two days and over 63 students came to learn how to solder. There were over 27 components to solder, and students showed a marked improvement between the first and last component soldered.Under the IEEE's guidance, students 

#### Lessons Learned

### Open Project Space

Open Project Space is an initiative began by the [IEEE at UCLA](https://openproject.space/about/), which is designed to teach students fundamental electrical engineering skills. As an instructor, I teach a workshop for 90 minutes a week for 5 weeks, with a new concept every week.

The series of workshops lead up to an internal micromouse competition in the spring, where students will construct an automatic maze solving mouse that will navigate the maze as fast as possible.

### Sponsorships

As secretary for the club, I am responsible for coordinating over \$3,000 worth of sponsorships from 2 companies - Alltest Instruments and TC Electric. Through Alltest Instruments, we recieved a instrument donation consisting of an 4-channel oscilloscope, a 300W DC Load, a current probe, and more, totalling \$2,700. 

### Club Trips
I have also secured over \$5,000 in funding from our Undergraduate Student Government and IEEE Long Island to attend two club trips. One trip took 15 students to the IEEE Region 1 MIT Micromouse competition, where two of our three competing teams took home the "2nd Place" and "Best Design" awards. Another trip took us to Marshall University for the IEEE Region 1 and Region 2 joint conference. Here, two teams attended, taking home a \$750 cash prize with 1st and 3rd place.

### Company Tours
We have conducted 2 companies so far, one to [Alltest Instruments](https://www.linkedin.com/feed/update/urn:li:activity:7136481568281227264/) and another to [Zebra Technologies](https://www.instagram.com/p/Czwkg-Gv0Xj/). For both of these, I was responsible for coordinating logistics and vehicular transport.