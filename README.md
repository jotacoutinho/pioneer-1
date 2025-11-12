# 🤖 Robot Navigation and Control System

This project implements a robot control and navigation system with support for autonomous movement, wall following, and collision avoidance. It integrates sensor fusion, logging, and visualization for simulation and real-world robotics experiments.

## 🧩 Overview

The robot operates in multiple modes, including:

Wander Mode – moves randomly while avoiding obstacles using sonar and laser sensors.

Wall Follow Mode – follows walls using a PID controller for distance regulation.

Manual Control – allows direct movement commands for debugging and teleoperation.

Playback Mode – replays previously recorded runs from log files.

## ⚙️ Features

Integration with ARIA for real or simulated robot control.

Sensor data processing from sonar and laser readings.

Path tracking and OpenGL-based visualization of the robot’s trajectory.

Logging system for recording and replaying odometry and sensor data.

Basic obstacle avoidance and wall-following PID control logic.

## 🛠 Tech Stack

C++ for control logic and system integration.

OpenGL (GLUT) for real-time visualization.

ARIA (ActivMedia Robotics Interface for Applications) for hardware/simulator communication.

## 📄 License

This project is open for educational and research use under the MIT License.
