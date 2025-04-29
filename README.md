# ADAS Simulation System 🚗🧠

## Overview
This project simulates an **Advanced Driver Assistance System (ADAS)** using **ROS2**, **Gazebo**, and **Computer Vision** techniques. The system replicates real-world driving conditions including lane markings, traffic lights, and road symbols for testing autonomous navigation capabilities.

## Features
- Lane Detection & Lane-Keeping Assist
- Traffic Light Recognition (Red, Green, Amber)
- Traffic Sign Detection (Speed limits, warnings)
- T-Junction Navigation using camera-based path planning
- Real-time Vehicle Control Simulation
- Modular ROS2 architecture with Gazebo and Blender integration

## Technologies Used
- **ROS2** – For communication and modular architecture
- **Gazebo** – 3D simulation of real-world traffic environments
- **Blender** – 3D modeling of traffic signs and lights
- **Python** – Computer vision logic
- **OpenCV** – Image processing

## Simulation Environment
Custom-built Gazebo environments include:
- Urban roads
- Lane-marked highways
- Traffic signs and signal placements

## File Structure
adas-simulation-system/
│
├── README.md
├── LICENSE (optional)
├── docs/                   # Images/screenshots, flowcharts, diagrams
│   ├── lane-detection.png
│   ├── t-junction-flowchart.png
│   └── final-model.jpg
│
├── simulation/
│   ├── models/             # .obj files from Blender
│   ├── worlds/             # .world and .sdf files from Gazebo
│   └── launch_files/
│       └── adas_launch.py
│
├── src/
│   ├── lane_detection.py
│   ├── traffic_light_detection.py
│   ├── t_junction_nav.py
│   └── sign_recognition.py
│
├── configs/
│   ├── ros2_params.yaml
│   └── gazebo_settings.yaml
│
└── report/
    └── SDP_ADAS_Report.pdf
