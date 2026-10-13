# Autonomous Mobile Robot Mission System

A robotics engineering project focused on reliable multi-goal autonomous navigation, failure recovery, and performance evaluation using ROS 2, Nav2, and Gazebo.

## Objectives

- Execute a sequence of navigation goals using Nav2.
- Track mission status, goal completion, and execution time.
- Implement navigation timeouts and cancellation.
- Support bounded retries and configurable failure policies.
- Record mission events and experiment results.
- Evaluate successful and failed navigation runs.
- Build automated tests and reproducible simulation experiments.

## Technology Stack

- Ubuntu Linux
- ROS 2 Jazzy
- Gazebo Sim
- Nav2
- Python
- Git and GitHub

## Development Status

**Phase 1 — Environment audit and project setup**

The existing ROS 2 environment is being inspected before implementation. Nav2 installation and robot simulation availability must be verified.

No navigation performance results are claimed at this stage.

## Planned Engineering Deliverables

- ROS 2 mission-management package
- Configuration files and launch instructions
- Automated tests
- Experiment logs in CSV format
- Performance analysis and plots
- Simulation recordings and documentation

## Project Principles

- Reuse Nav2 for navigation rather than reimplementing its planner or controller.
- Handle failures explicitly and avoid unlimited retries.
- Keep experiments reproducible.
- Report measured results honestly.
