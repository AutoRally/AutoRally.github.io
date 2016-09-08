---
layout: single
title: ""
permalink: /build/

header:
  image: electronicsBox.png

---

# Build your own AutoRally Platform

The AutoRally platform is designed to be constructed by a small team of undergraduate or graduate students with engineering or computer science backgrounds. A complete platform comprised of a chassis and Mini-ITX compute box can be constructed and configured in about 100 hours.

Documentation is separated into a few parts, all of which are contained in two GitHub repositories  along with all supplemental files. 

  * [Platform build instructions](https://github.com/AutoRally/autorally_platform_instructions)
    * Chassis instructions and supporting materials
    * Mini-ITX compute box instructions and supporting materials
    * Complete parts list
    * Files for 3D printing and fabrication
    * Operating Procedures
  * [Code and software tutorials](https://github.com/AutoRally/autorally)
    * [Platform configuration instructions](https://github.com/AutoRally/autorally/wiki) to configure a completed platform
    * Core software to run the platform
    * State estimator built with [GTSAM](https://collab.cc.gatech.edu/borg/) that fuses GPS and IMU measurements
    * GPS waypoint steering controller and constant velocity throttle controller
    * Gazebo-based simulation environment with vehicle model
