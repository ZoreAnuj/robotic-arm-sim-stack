# Robotic Arm Simulation Stack

A ROS2-based simulation stack for a 7-DOF robotic arm, forked from the original BCR Arm project. This project explores modern robotic simulation, motion planning, and hardware integration within a standardized ROS2 Control framework.

## Key Features
*   Full simulation in Gazebo (Fortress/Harmonic) and NVIDIA Isaac Sim.
*   Integrated motion planning and execution using MoveIt 2.
*   ROS2 Control interfaces for simulated and real hardware.
*   Multi-ROS2 distribution support (Humble, Jazzy).

## Tech Stack
ROS2 (Humble/Jazzy), Gazebo, MoveIt 2, ROS2 Control, NVIDIA Isaac Sim

## Getting Started
```bash
# Clone the repository
git clone https://github.com/zoreanuj/robotic-arm-sim-stack.git
cd robotic-arm-sim-stack
# Build with colcon
colcon build --symlink-install
source install/setup.bash
# Launch the simulation
ros2 launch bcr_arm_gazebo gazebo.launch.py
```