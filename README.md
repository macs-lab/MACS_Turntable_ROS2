# MACS_Turntable_ROS2

Hardware:
1. Find turntable examples and design drive train. (Stepper motor is likely best option for actuation)
2. Table design should be modular, able to be swapped for larger/smaller options depending on part size and fixturing.
3. Optimize for angular precision. Camera field of view is very small, therefore error in rotational precision of the part under inspection is important. Shoot for sub-1mm error at outer diameter of turntable. Gearbox could be used to improve precision.

Hardware Integration Steps:
1. Get acquianted with the basics of ROS2
- [Getting started with ROS2 Humble](https://docs.ros.org/en/humble/index.html)
2. micro-ROS
- [Getting started with micro-ROS](https://micro.ros.org/docs/tutorials/core/overview/)
- [Robot control using PlatformIO and ESP32](https://www.youtube.com/watch?v=Nf7HP9y6Ovo)

Control:
1. The turntable will need to be able to follow a joint trajectory. This will require the hardware to receive and track a reference position and send its current position back to the controller at a fixed rate as feedback.
- [Joint Trajectory Controller](https://control.ros.org/master/doc/ros2_controllers/joint_trajectory_controller/doc/userdoc.html)
- [Using Motors in Robotics](https://www.youtube.com/watch?v=-PCuDnpgiew)