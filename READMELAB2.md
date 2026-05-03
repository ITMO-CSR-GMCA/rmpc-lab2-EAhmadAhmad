# Lab #2: Robot Motion Planning and Control — UR5 Manipulator

## Overview

This project presents Laboratory Work #2 for Robot Motion Planning and Control using the UR5 industrial manipulator model in Python.

The lab focuses on kinematic analysis, workspace construction, inverse kinematics, and trajectory planning. The implementation is performed in a Jupyter Notebook using the Robotics Toolbox for Python.

---

## Objectives

The main objectives of this lab are:

- Load the UR5 manipulator model
- Define kinematic and dynamic robot parameters
- Set an arbitrary initial robot configuration
- Solve the forward kinematics problem
- Construct the robot workspace under joint constraints
- Select a reachable target point inside the workspace
- Solve the inverse kinematics problem
- Plan trajectories using multiple planning methods
- Plot joint position, velocity, and acceleration profiles
- Analyze and compare the obtained results

---

## Robot Model

The selected manipulator is the **UR5** robot.

The robot model includes:

- Denavit–Hartenberg parameters  
- Link masses  
- Centers of mass  
- Inertia tensors  
- Motor inertias  
- Viscous friction coefficients  
- Coulomb friction coefficients  
- Gear ratios  
- Joint limits  

---

## Implemented Methods

The following trajectory planning methods are implemented and compared:

1. **jtraj** — joint-space polynomial interpolation  
2. **Trapezoidal velocity profile** — acceleration → constant velocity → deceleration  
3. **Quintic polynomial trajectory** — smooth trajectory with continuous acceleration  
4. **Cartesian straight-line trajectory** — end-effector path planning with inverse kinematics  

---

## Project Structure

```text
.
├── Lab2.ipynb
|__ README.md
