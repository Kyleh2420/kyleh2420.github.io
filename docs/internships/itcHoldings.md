---
title: ITC Holdings
layout: default
parent: Internships
nav_order: 2022-08-18
#has_children: true
---

# About
![A photo of a bucket truck and mobile crane.]({{ site.baseurl }}/assets/images/ITC/bucketTruck.jpg)
*ITC took the interns on a field trip to the Iowa City Warehouse, where we got to understand the hardships of being in the field. Yes, I got to go up 100ft in the bucket truck and operate the mobile crane.*


In Summer 2022, I moved to Cedar Rapids, Iowa to work at ITC Midwest, a subsidiary of ITC Holdings. Headquarted in Novi, Michigan, ITC is a midwest transmission line owner/operator. At ITC Midwest, I worked on the line design team.

On the line design team, I was assigned to update Plan and Profiles from the early 1990s with modern information from a LIDAR point cloud.  Using this information, I would generate new as-builts to keep information up to date. Additionally, I was assigned to study galloping, and the effect of T2-ACSR conductors in mitigating galloping.

## Galloping Analysis

Galloping is a phenomena where ice build-up on power lines cause the wind to catch in a certain way. The wind pushes the conductors around and builds energy, eventually turning all 3-phase conductors into a jumprope situation. For obvious reasons, this is bad. Conductors could touch, sheer, hit external objects causing tripped breakers and downing lines. An example of galloping can be found here: [galloping example](https://www.youtube.com/watch?v=GEGbYRii1d4).

![Normal ACSR conductors]({{ site.baseurl }}/assets/images/ITC/ACSR.jpg)
*Normal ACSR Conductors*

T2 conductors are proposed as a solution to galloping. As the wind blows, the two conductors move individually, sheering off any ice buildup. This in turn limits the wind's effect on the hanging conductors. 

While effective, this method does end up doubling the cable used, and therefore the price. To verify that T2 conductors were working, I was tasked with combing through a 13,000+ row excel sheet of past outages to analyze the effectiveness of T2.

![T2-ACSR conductors]({{ site.baseurl }}/assets/images/ITC/T2ACSR.jpg)
*T-2 ACSR Conductors. Notice the winding and crossing the two conductors.*

### Answer: It works

Though heavy use of automation using Python and Excel shortcuts, I found that T2 indeed is worth double the cost. over 94% of the downed galloping lines were made with regular Aluminum Conductor Steel Reinforced (ACSR) conductors. The other 6% that galloped were T2-ACSR condutors, but were repeated lines, indicating that the circut was paticularly susceptible to high ice and high winds.

## Photos

![A poletop switch.]({{ site.baseurl }}/assets/images/ITC/switch.jpg)
*A massive 10ft tall pole top switch. Like a normal light switch, the contacts would open to isolate the circuit.*

![Me hanging up a lockout tag.]({{ site.baseurl }}/assets/images/ITC/lockoutTagout.jpg)
*As a part of experiencing the field, the field supervisor had us emulate hanging up a lockout/tagout device on a switch. It was difficult.*

![A mobile crane being opeated]({{ site.baseurl }}/assets/images/ITC/lockoutTagout.jpg)
*As another simulation, the interns had to operate a crane with a load on the end as smoothly as possible. My load ended up penduluming everywhere.*
