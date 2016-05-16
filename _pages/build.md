---
layout: single
title: ""
permalink: /build/

header:
  image: electronicsBox.png

---

# Build your own AutoRally Platform

The AutoRally platform can be constructed by a small team of non-pofessionals. Documentation is broken into a few parts, all of which are contained in a GitHub repository with all necessary supporting documents. The current platform with high-precision sensors and Mini-ITX form-factor compute box can be built and ready to run in about 80 hours.

  * [Platform build instructions](https://github.com/AutoRally/autorally_platform_instructions) include:
    * Chassis instructions and supporting materials
    * Mini-ITX compute box instructions and supporting materials (Coming soon)
    * Complete parts list
    * Operating Procedures (Coming soon)
  * [Code](https://github.com/AutoRally/autorally)
    * Core software to run the platform
    * Sate estimator built with [GTSAM](https://collab.cc.gatech.edu/borg/) that fuses GPU and IMU measurements
    * GPS waypoint steering controller and constant velocity thorttle controller
    * Simulation environment with vehicle model
  * [Platform configuration instructions](https://github.com/AutoRally/autorally/wiki)
    * Setup a platform
