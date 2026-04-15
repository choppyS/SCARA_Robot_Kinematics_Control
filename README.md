# Kinematics, Dynamics and Control of a SCARA Manipulator

This repository contains the full technical project for the "Foundations of Robotics" course. It covers the complete engineering cycle of a 4-DOF SCARA (Selective Compliance Assembly Robot Arm), from mathematical modeling to advanced motion control.

## 🤖 Project Overview
The project focuses on the analysis and simulation of a SCARA robot, implementing:
* **Kinematic Modeling:** Direct kinematics (Denavit-Hartenberg), analytical Jacobian, and reachable workspace analysis.
* **Manipulability:** Evaluation of velocity and force ellipsoids to identify dexterity and singular configurations.
* **Trajectory Planning:** Generation of complex paths including straight lines, circular arcs, and multiple via-points.
* **CLIK Algorithms:** Implementation of Closed-Loop Inverse Kinematics using Jacobian Inverse, Transpose, and Pseudo-Inverse (for redundancy resolution).

## 🎮 Advanced Motion Control
The dynamic model is derived and used to design and compare three different control architectures:
1. **Robust Control:** To handle model uncertainties and external disturbances.
2. **Adaptive Control:** To compensate for unknown or varying payloads (e.g., a 3kg end-effector load).
3. **Inverse Dynamics Control:** Operational space control with integral action to eliminate steady-state errors.

## 💻 Software & Tools
* **MATLAB:** Algorithm development and CLIK implementation.
* **Simulink:** Dynamic simulation of the controlled manipulator with discrete-time controllers (1ms sampling).

## 📄 Repository Contents
* `FoRTechnicalProject.pdf`: Detailed technical report with mathematical derivations and plots.
* `ProjectFoR24.pdf`: Project specifications and theoretical framework.
* `TechnicalProject.zip`: Complete MATLAB scripts and Simulink models.

---
*Developed for the Master's Degree in Automation Engineering at the University of Naples Federico II, under the supervision of Prof. Bruno Siciliano.*
