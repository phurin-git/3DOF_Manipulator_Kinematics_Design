# 3DoF Robot Control Design

This repository contains a comprehensive design and control system for a 3 Degrees of Freedom (3DoF) robotic arm. The project utilizes advanced mathematical concepts and control theories to model, analyze, and control the robot's movement. Key components include rotation matrices, homogeneous transformations, Denavit-Hartenberg parameters, Jacobians, potential energy calculations, and dynamic modeling using the Euler-Lagrange method.
## Features

- **Rotation Matrix:** Computes and applies rotation matrices to describe the orientation of the robot's links.
- **Homogeneous Transformation:** Utilizes homogeneous transformation matrices to describe the robot's kinematics and the position of the end-effector.
- **Denavit-Hartenberg Parameters:** Implements DH parameters to simplify the kinematic modeling of the robotic arm.
- **Jacobian Matrix:** Calculates the Jacobian matrix for relating joint velocities to end-effector velocities.
- **Potential Energy:** Determines the potential energy of the robotic system based on its configuration.
- **Dynamic Model:** Constructs the dynamic model using the Euler-Lagrange method to derive the equations of motion.
- **Dynamic Equations:** Utilizes Python libraries (NumPy and SymPy) to calculate and simplify the dynamic equations governing the robot's movement.