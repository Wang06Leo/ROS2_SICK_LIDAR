# ROS2_LIDAR_SDK
ROS2 SDK to enable integration with LiDAR Smart Sensors for robotics and autonomous systems 

## Main features and characteristics:
- ROS2 LiDAR Driver Package (in C++ or Python)
- Point Cloud Processing & Filtering Nodes
- Calibration & Diagnostic Tools
- Multi-LiDAR Synchronization Module

## Installations
ROS2 HUMBLE:
- https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debs.html

sick_scan_xd:
- https://github.com/SICKAG/sick_scan_xd?tab=readme-ov-file#ros-2-install-prebuilt-binaries

Wireshark (For finding ip address for lidars):
```bash
# To install WireShark 
sudo apt update
sudo apt install wireshark
```
## Before start
```bash
# Make a ROS 2 workspace for this lidar sdk
mkdir -p lidar_ws/src  
# Clone the repository into your ROS 2 workspace
cd lidar_ws/src
git clone https://github.com/your-org/ROS2_LIDAR_SDK.git

# Build the SDK
cd ~/lidar_ws
colcon build 

# Source the setup file
source install/setup.bash

