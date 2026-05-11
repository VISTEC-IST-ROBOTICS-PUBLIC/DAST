# A Differential Steering Mechanism for Directional Adaptation and Self-Organized Locomotion under Decentralized Control in Legged Robots

This repository contains the simulation environment and controller implementation for the paper:

> **A Differential Steering Mechanism for Directional Adaptation and Self-Organized Locomotion under Decentralized Control in Legged Robots**

The project presents a decentralized locomotion control framework with a Differential Adaptive Steering Technique (DAST) for directional adaptation in a stick insect-like robot.

---

## Overview

This repository provides:

- ROS1-based controller implementation
- CoppeliaSim simulation environment
- Simulated stick insect-like robot model
- DAST controller package
- Self-organized locomotion framework

The simulation was developed and tested using:

- **Ubuntu 20.04**
- **ROS1**
- **CoppeliaSim**

---

## Main Files

For a quick understanding of the project, please see the following files:

### Controller Implementation
- `duallearner.cpp`  
  Main implementation of the DAST controller and adaptive steering mechanism.

### Robot Control Script
- `medaextra_optimize.lua`  
  Lua script used for robot control and communication within CoppeliaSim.

### Simulation Scene
- `medaextra_ver1.ttt`  
  Main CoppeliaSim scene file containing the simulated stick insect-like robot and experimental environment.

---
