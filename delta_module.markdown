---
layout: page
title: 2x2 Delta Module
permalink: /delta_module/
nav_order: 2
---
# Tutorial for Assembly of 2x2 Delta Robot Module
<a target="_blank" href="{{ site.baseurl }}/cad/quad_delta.png"><img src="{{ site.baseurl }}/cad/quad_delta.png"  width="20%" height="20%"/></a>

Component list for a 2x2 delta robot module assembly:

| Name                                                   | Number | Link                                |
| ------------------------------------------------------ | ------ | ----------------------------------- |
| Actuonix L12 100mm Linear Servo                        | 12     |                                     |
| FDM printed enclosure                                  | 1      |                                     |
| FDM printed star-shaped mounts                         | 4      |                                     |
| Adafruit Feather M0                                    | 1      |                                     |
| Adafruit FeatherWing DC and Stepper Motor Driver       | 3      |                                     |
| ADS1015 ADC                                            | 3      |                                     |
| Plexiglass Delta Module Holder                         | 1      |                                     |
| 8-32 ½” Button Head Screw (Pack of 100)                | 1      | [McMaster](https://www.mcmaster.com/92949A194/) |
| Female Threaded Standoff 3-½” Long, 8-32 Thread        | 5      | [McMaster](https://www.mcmaster.com/91115A839/) |
| Male-Female Threaded Standoff 1-½" Long, 8-32 Thread   | 5      | [McMaster](https://www.mcmaster.com/91075A458/) |
| 8-32 ⅞” Button Head Screw (Pack of 100)                | 1      | [McMaster](https://www.mcmaster.com/92949A198/) |
| 8-32 Hex Nut (Pack of 100)                             | 1      | [McMaster](https://www.mcmaster.com/91841A009/) |
| SLA printed fingertip clip                             | 4      |                                     |
| FDM printed soft parallelogram links                   | 4      |                                     |
| FDM printed fingertips                                 | 4      |                                     |


Click on the respective images to download their CAD files.

### FDM 3D Printed Components
##### FDM printed star-shaped mounts

<a target="_blank" href="{{ site.baseurl }}/cad/FDM%20Printed%20Star%20Shaped%20Mount.STEP"><img src="{{ site.baseurl }}/cad/FDM%20Printed%20Star%20Shaped%20Mount.png"  width="40%" height="40%"/></a>

##### FDM printed soft parallelogram links

<a target="_blank" href="{{ site.baseurl }}/cad/FDM%20Printed%20Delta%20Link.STEP"> <img src="{{ site.baseurl }}/cad/FDM%20Printed%20Delta%20Link.png"  width="40%" height="40%" /></a>

##### FDM printed fingertips

<a target="_blank" href="{{ site.baseurl }}/cad/FDM%20Printed%20Fingertip.STEP"> <img src="{{ site.baseurl }}/cad/FDM%20Printed%20Fingertip.png"  width="15%" height="15%" /></a>

### SLA 3D Printed Components
##### SLA printed fingertip clip

<a target="_blank" href="{{ site.baseurl }}/cad/SLA%20Printed%20Fingertip%20Clip.STEP"> <img src="{{ site.baseurl }}/cad/SLA%20Printed%20Fingertip%20Clip.png"  width="30%" height="30%" /></a>

### Laser Cut Components
##### Plexiglass delta robot holder

<a  target="_blank" href="{{ site.baseurl }}/cad/top_plate2x2.dxf"> <img src="{{ site.baseurl }}/cad/top_plate_2x2.png"  width="30%" height="30%" /></a>

### Orderable Components

##### Actuators
[Actuonix L12 100mm Linear Servo](https://www.actuonix.com/l12?sn=166599480&e=cor&ajx=1&nsrt=CID_N1&ontd=2&tag=XIDSC138)

##### Electronics
[Adafruit Feather M0](https://www.adafruit.com/product/2772)

[Adafruit FeatherWing DC and Stepper Motor Driver](https://www.adafruit.com/product/2927)

[Adafruit ADS1015 ADC](https://www.adafruit.com/product/1083)

Power Shield

## Assembly
* Attach sets of 3 linear actuators to 4 star-shaped mounts using 8-32 screws.
* Insert the 12 actuators into the square shaped holes of 2 [Plexiglass delta robot holders](#laser-cut-components). (note this will be difficult as the tolerances are small)
* Attach the 1-½" Long spacers between the star-shaped mounts and the lower plexiglass holders in the formation shown below: 

<img src="{{ site.baseurl }}/cad/spacers2.png"  width="60%" height="60%" />

* Attach the 3-½" Long spacers between the 2 plexiglass holders.
* Attach the delta links to the linear actuators. 
* Attach the [Fingertip Clip Holders](#sla-printed-fingertip-clip) to the end effector plates of the delta robots and super glue the [Fingertips](#fdm-printed-fingertips) on top as shown below:

<img src="{{ site.baseurl }}/cad/clip.png"  width="40%" height="40%"/>
<img src="{{ site.baseurl }}/cad/clip_finger.png"  width="35%" height="35%"/>

* Follow along [This Guide]({{ site.baseurl }}/electronics/delta_shield_introduction.pdf){:target="_blank"} to learn how to put the electronics together.
* Use the [modified delta shield]({{ site.baseurl }}/electronics/single_delta_shield.zip) to produce the PCB for distributing the power to all motors, attach ADC and motor drivers similar to single shield design and short all the VCC and GND pins manually.
* The final result should look like this: 

<a href="{{ site.baseurl }}/cad/quad_delta.png" target="_blank"><img src="{{ site.baseurl }}/cad/quad_delta.png"  width="20%" height="20%"/></a>