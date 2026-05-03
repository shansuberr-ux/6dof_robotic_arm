# 6-DOF Mimicking Robotic Arm

> **Mechanism Design · Embedded Systems · Arduino · Real-Time Control**

A 6-degrees-of-freedom robotic arm that mirrors the operator's movements in real time, with trajectory recording and repeatable playback functionality. Built as a personal R&D project to explore human-robot motion mirroring.

---

## Project Overview

| Item | Detail |
|---|---|
| **Degrees of Freedom** | 6 |
| **Control Mode** | Real-time mirroring + trajectory playback |
| **Platform** | Arduino-based embedded system |
| **Status** | Functional prototype |

---

## Features

- **Real-time motion mirroring** — operator arm movements captured and replicated with minimal latency
- **Trajectory recording** — full movement sequences logged to memory
- **Playback** — recorded trajectories replayed autonomously and repeatably
- Modular joint design for easy reconfiguration
- Custom kinematics for accurate end-effector positioning

---

## How It Works

1. Sensors on the operator-side exoskeleton capture joint angles across all 6 DOF
2. Angle data is processed and mapped to servo commands in real time
3. Servos at each joint replicate the motion on the robot arm
4. In record mode, all joint angle sequences are logged
5. On playback, the stored sequence drives all servos through the recorded trajectory

---


## Gallery

| The prototype |
| ![Physical Proto](https://github.com/shansuberr-ux/6dof_robotic_arm/blob/main/6dof%20robot.jpg). 

---

## Skills Demonstrated

`Mechanism Design` `Arduino` `Servo Control` `Kinematics` `Embedded C/C++` `Prototyping` `Sensor Integration`
