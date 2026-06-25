# Self Balancing Robot on ROS using PID Controller

Robotic System & Programming Lab project. Self balancing robot (inverted pendulum
problem) simulated on ROS (Robot Operating System), controlled using PID
(Proportional Integral Derivative) controller.

**Bahria University Karachi Campus**
Department of Electrical Engineering
Course: Robotic System & Programming Lab, Fall 2025
Class: BS(R&IS)-5A

Team:
- Malahima Adeel (02-239232-043)
- Urooj Khan (02-239232-052)
- Shayan Ali (02-239232-068)

Submitted to: Sir Hamza

## Overview
A self balancing robot needs constant correction to stay upright, classic inverted
pendulum control problem in robotics. This project builds and simulates that system
in ROS, using a PID controller to continuously correct the robot's tilt and keep it
balanced.

## Report Contents
- Abstract
- Introduction
- Literature Review
- Components and Tools Description
- Methodology (Proposed Model, Circuit/Simulation Diagram and Description)
- Results and Discussion
- Conclusion and Future Work
- Project Pictures
- References

Full report: `Self_Balancing_Robot_Report.pdf`

## Simulation
See `simulation_video.mp4` for the robot balancing in ROS simulation.

## Limitation
Robot achieves initial balance in simulation but drifts after a short duration.
Exact cause not fully isolated yet, possible factors include PID gain tuning,
sensor noise, or simulation parameters. Listed as future work for further
debugging and tuning.

## Tools Used
- ROS (Robot Operating System)
- PID Control Theory
- Robot simulation environment

## Files
- `Self_Balancing_Robot_Report.pdf` — full project report
- `simulation_video.mp4` — simulation demo
