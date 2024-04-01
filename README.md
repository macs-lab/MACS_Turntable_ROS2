# MACS_Turntable_ROS2

Hardware:
1. Find turntable examples and design drive train. (Stepper motor is likely best motor option)
2. Table design should be modular, able to be swapped for larger/smaller options depending on part size and fixturing.
3. Optimize for angular precision. Camera field of view is very small, therefore error in rotational precision of the part under inspection is important. Shoot for sub-1mm error at outer diameter of turntable

Steps:
1. Get acquianted with the basics of ROS2
- [Getting started with ROS2 Humble](https://docs.ros.org/en/humble/index.html)
2. micro-ROS
- [Robot control using PlatformIO and ESP32](https://www.youtube.com/watch?v=Nf7HP9y6Ovo)