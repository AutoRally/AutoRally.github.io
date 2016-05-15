---
layout: single
title: Platform Specs
permalink: /specs/

---

![im]({{ site.url }}{{ site.baseurl }}/images/autorally_platform_nobody.jpg)

  * Weight: 21kg
  * Top speed: 27m/s (60 mph)
  * Size: 1m long, 0.6m wide, 0.4m high
  * Standard operating team: 2-3 people


## Chassis
  * Derived from 1:5 scale RC truck
  * Off-the-shelf chassis modifications to support payload
  * Custom 3D printed mounts and enclosures
  * 4s 6500mAh battery pair give typical run time of 3 hours, full-load run time 45 min
  * Seamless switching between autonomous and manual control using RC transmitter
  * Remote run stop disables motion in manual and autonomous modes

## Sensor Suite
  * High-precision IMU, raw data up to 1KHz
  * RTK-corrected GPS, position at 20Hz
  * Hall-effect rotation sensor on each wheel at 70Hz
  * 2 front facing machine vision cameras, 1280x1024, 70fps, global shutter, synchronously triggered

## Computing (Mini-ITX)
<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/images/computeBoxExterior.jpg" alt="">
</figure> 

  * Intel Skylake Quad-core i7
  * 32GB DDR4 RAM
  * 512GB m.2 SSD
  * 1TB SATA3 SSD
  * Nvidia GTX 750ti GPU
  * WiFi and XBee communication
  * 6s 11000mAh battery gives typical run time of 3 hours, full-load run time 1 hour

<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/images/computeBoxInterior.jpg" alt="">
</figure>
  * Dynamically switching power selection between internal battery and external power
  * Robust fabricated aluminum enclosure protects sensitive electronics from shock
  * Standardized mounting and communication interface to chassis

## Software
  * ROS-compatible, open-source core code
  * State estimation by fusing IMU and GPS using GTSAM optimization toolbox
  * Flexible launch system to pair any compute box with any chassis
  * Operator Control Station (OCS) for remote monitoring
  * GPS waypoint steering controller
  * Constant velocity controller

## Simulation

<figure style="width: 400px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/images/trackSimulation.jpg" alt="">
</figure>

  * Gazebo-based
  * Identical ROS interface as physical robot
  * Vehicle model paramters measured from physical robot