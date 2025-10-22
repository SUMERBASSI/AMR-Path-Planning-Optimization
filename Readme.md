AMR Path Planning Optimization in ROS 2

This repository contains the project files for the B.Tech. Project: "AMR Path Planning Optimization: Layout Comparison & Energy Analysis" from the Indian Institute of Technology Ropar.

The project develops and evaluates path planning optimization strategies for Autonomous Mobile Robots (AMRs) in warehousing and vertical farming contexts. It compares three distinct layouts (Grid, Fishbone, Serpentine) and three path planning algorithms (A*, RRT*, D* Lite) to analyze travel distance and energy consumption.

Tech Stack

Framework: ROS 2 Jazzy

Simulation: Gazebo 11

Visualization: RViz

Robot Model: Novus Carry AMR

OS: Ubuntu 24.04.3 LTS

Languages: Python, C++ (for ROS nodes), XML (for launch/config)

Analysis: Python (Pandas, Matplotlib)

Features

3 Warehouse Layouts: Gazebo world files for Grid, Fishbone, and Serpentine layouts.

Path Planning Algorithms: ROS 2 node implementations for A*, RRT*, and D* Lite.

Energy Analysis: Python scripts to collect and analyze simulation data (travel distance, time, energy) to compare layout and algorithm performance.

Realistic Simulation: Utilizes a model of the Novus Carry AMR with LIDAR-based navigation.

Setup and Installation

Prerequisites

Ubuntu 24.04.3 LTS

ROS 2 Jazzy (Follow the official installation guide)

Gazebo 11

Python 3.8+ with pandas and matplotlib

pip install pandas matplotlib


Build from Source

Clone the repository into your ROS 2 workspace's src folder:

cd ~/ros2_ws/src
git clone [https://github.com/YOUR_USERNAME/amr-path-planning.git](https://github.com/YOUR_USERNAME/amr-path-planning.git)


Project Team

Rahul Yadav (2022MEB1334)

Sumer Bassi (2022MCB1351)

Supervisor

Dr. Ekta Singla
Department of Mechanical Engineering, IIT Ropar

License

This project is licensed under the MIT License. See the LICENSE file for details.
