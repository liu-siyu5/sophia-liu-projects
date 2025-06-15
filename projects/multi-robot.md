# Synchronization & Coordination of Two Mobile Robots

**Duration:** October 2024 – December 2024  
**Location:** Boston

## Overview
Multi-robot SLAM system enabling coordinated mapping and navigation for two TurtleBot3 robots.

## Technical Details
- Configured dual‑TurtleBot3 SLAM stack in ROS 1/Gazebo
- gmapping + AMCL + move_base for autonomous mapping and navigation
- Engineered multi‑robot integration with namespace‑isolated launch files
- Custom map_merge node fused two occupancy grids into one live map
- Eliminated TF‑frame collisions
- Debugged cross‑package TF/topic conflicts (slam_gmapping ↔ explore_lite)

## Technologies Used
- ROS 1 / Gazebo
- TurtleBot3
- gmapping, AMCL, move_base
- Custom map merging algorithms
- Multi-robot coordination
- SLAM (Simultaneous Localization and Mapping)

## Results
- Successful dual-robot autonomous navigation
- Real-time collaborative mapping
- Robust multi-robot coordination system
