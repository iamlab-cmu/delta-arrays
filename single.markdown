---
layout: page
title: Single Delta Robots
permalink: /single_delta_robots/
nav_order: 1
---

Component list for a single delta robot assembly:

| Name                                                   | Number | Link                                |
| ------------------------------------------------------ | ------ | ----------------------------------- |
| Actuonix L12 100mm Linear Servo                        | 3      |                                     |
| FDM printed star-shaped mounts                         | 1      |                                     |
| Adafruit Feather M0                                    | 1      |                                     |
| Adafruit FeatherWing DC and Stepper Motor Driver       | 1      |                                     |
| ADS1015 ADC                                            | 1      |                                     |
| Plexiglass Delta Holder                                | 1      |                                     |
| 8-32 ½” Button Head Screw (Pack of 100)                | 1      | [McMaster](https://www.mcmaster.com/92949A194/) |
| Female Threaded Standoff 3-½” Long, 8-32 Thread        | 3      | [McMaster](https://www.mcmaster.com/91115A839/) |
| Male-Female Threaded Standoff 1-1/2" Long, 8-32 Thread | 3      | [McMaster](https://www.mcmaster.com/91075A458/) |
| 8-32 ⅞” Button Head Screw (Pack of 100)                | 1      | [McMaster](https://www.mcmaster.com/92949A198/) |
| 8-32 Hex Nut (Pack of 100)                             | 1      | [McMaster](https://www.mcmaster.com/91841A009/) |
| SLA printed fingertip clip                             | 1      |                                     |
| FDM printed soft parallelogram links                   | 1      |                                     |
| FDM printed fingertips                                 | 1      |                                     |

Click on the respective images to download their CAD files.

### FDM 3D Printed Components
FDM printed star-shaped mounts

<a href="{{ site.baseurl }}/cad/FDM%20Printed%20Star%20Shaped%20Mount.STEP"><img src="{{ site.baseurl }}/cad/FDM%20Printed%20Star%20Shaped%20Mount.png"  width="40%" height="40%"/></a>

FDM printed soft parallelogram links

<a href="{{ site.baseurl }}/cad/FDM%20Printed%20Delta%20Link.STEP"> <img src="{{ site.baseurl }}/cad/FDM%20Printed%20Delta%20Link.png"  width="40%" height="40%" /></a>

FDM printed fingertips

<a href="{{ site.baseurl }}/cad/FDM%20Printed%20Fingertip.STEP"> <img src="{{ site.baseurl }}/cad/FDM%20Printed%20Fingertip.png"  width="15%" height="15%" /></a>

### SLA 3D Printed Components
SLA printed fingertip clip

<a href="{{ site.baseurl }}/cad/SLA%20Printed%20Fingertip%20Clip.STEP"> <img src="{{ site.baseurl }}/cad/SLA%20Printed%20Fingertip%20Clip.png"  width="30%" height="30%" /></a>

### Laser Cut Components
Plexiglass delta robot holder

<a href="{{ site.baseurl }}/cad/delta_mount.STEP"> <img src="{{ site.baseurl }}/cad/delta_mount.png"  width="30%" height="30%" /></a>

### Orderable Components + Assembly

##### Actuators
[Actuonix L12 100mm Linear Servo](https://www.actuonix.com/l12?sn=166599480&e=cor&ajx=1&nsrt=CID_N1&ontd=2&tag=XIDSC138)

##### Electronics
[Adafruit Feather M0](https://www.adafruit.com/product/2772)

[Adafruit FeatherWing DC and Stepper Motor Driver](https://www.adafruit.com/product/2927)

[Adafruit ADS1015 ADC](https://www.adafruit.com/product/1083)

Power Shield

##### Assembly
* Print a star shaped connector on the 3D printer using the default fine printing settings for PLA on your 3D printer.
* Attach the 3 linear actuators to the star shaped mount as shown below:
<img src="{{ site.baseurl }}/cad/mounted_actuators.png"  width="30%" height="30%" />

* Insert the 3 linear actuators through the 3 holes in the delta robot holder plexiglass cutout, spaced apart using the 3-½” Long Standoff.
* Attach the 3 legs of the parallelogram delta links to each of the linear actuators using 8-32 ½” screws and nuts.
* Follow along [This Guide]({{ site.baseurl }}/electronics/delta_shield_introduction.pdf){:target="_blank"} to learn how to put the electronics together 
* Use the [single delta shield]({{ site.baseurl }}/electronics/single_delta_shield.zip) to produce the PCB