---
layout: single
title: ""
permalink: /build/

header:
  image: electronicsBox.png

---

# Build your own AutoRally Platform

The AutoRally platform is designed to be constructed by a small team of undergraduate or graduate students with engineering or computer science backgrounds. The current AutoRally platform (chassis + Mini-ITX compute box) can be constructed and configured in about 80 hours.

Documentation is separated into a few documents, all of which are contained in a two GitHub repositories with all necessary supporting documents. 

  * [Platform build instructions](https://github.com/AutoRally/autorally_platform_instructions)
    * Chassis instructions and supporting materials (Coming soon)
    * Mini-ITX compute box instructions and supporting materials (Coming soon)
    * Complete parts list (Coming soon)
    * Operating Procedures (Coming soon)
  * [Code](https://github.com/AutoRally/autorally)
    * Core software to run the platform
    * Sate estimator built with [GTSAM](https://collab.cc.gatech.edu/borg/) that fuses GPU and IMU measurements
    * GPS waypoint steering controller and constant velocity throttle controller
    * Simulation environment with vehicle model
  * [Platform configuration instructions](https://github.com/AutoRally/autorally/wiki)
    * Compute box setup information so the core software can communicate with a chassis
