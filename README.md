# Autonomous edge detection robot
Autonomous edge detection robot that senses and avoids edges using IR/ultrasonic sensors for safe navigation.

# Edge Detection Robot (Line & Cliff Avoidance System)

The Edge Detection Robot is an intelligent autonomous bot designed to detect and avoid edges or cliffs, preventing accidental falls from elevated surfaces. It uses infrared (IR) or ultrasonic sensors to continuously monitor the surface and automatically stop or change direction when an edge is detected.

This robot demonstrates basic principles of autonomous navigation, sensor-based decision making, and embedded control systems — ideal for robotics learning and automation applications.

# Features

-Automatic edge and cliff detection using IR/ultrasonic sensors

- Microcontroller-based real-time decision system (Arduino/ESP32)

- Battery-powered with efficient motor driver control

- Self-stopping and rerouting on detecting drop edges

- Compact, safe, and beginner-friendly design

# Components Used

- Microcontroller: Arduino Uno / ESP32

- Sensors: IR / Ultrasonic Sensors (for edge detection)

- Motors: DC Motors with Motor Driver (L298N / L293D)

- Chassis: 2WD / 4WD Robot Base

- Power Supply: Li-ion Battery / 9V

# Working Principle

The robot continuously reads sensor values to check for surface presence.

When the sensor detects no reflected signal (edge detected), the controller halts motor movement.

The robot reverses or turns in another direction to stay within the safe boundary.

# Applications

Autonomous navigation systems

Educational robotics projects

Safety bots for elevated surfaces

Obstacle and fall-prevention demonstrations

Developed as part of a robotics automation project focusing on intelligent motion and sensor-based safety mechanisms.