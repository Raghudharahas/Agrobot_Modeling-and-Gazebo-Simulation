# 🤖 Agrobot

Agrobot contributes significantly to the modernization of agriculture by enhancing productivity, scalability, and precision farming practices. Beyond its role in automating fruit picking, the robot provides real-time data that enables farmers to optimize resource use and reduce environmental impact. The incorporation of robotics in agriculture, exemplified by Agrobot, showcases the transformative potential of technology in revolutionizing traditional farming methods. By alleviating labour constraint...

Our project aims to design and implement a robot capable of identifying and selectively picking ripe fruits from trees and collecting them in a bin, streamlining the harvesting process and reducing the reliance on manual labour. This is done by integrating a manipulator arm (UR-10) into a mobile robot.

![Agrobot Image](https://github.com/user-attachments/assets/d31d96ae-508f-48d1-8ffc-ae8a56d4e7aa)

## 🔧 Robot Architecture

- **Mobile Platform**: 4-wheel drive system for stability and mobility.
- **Steering System**: Front two wheels are steerable for better navigation in tight spaces.
- **Robotic Arm – UR10**: Provides 6 degrees of freedom with precision and versatility.
- **End Effector – Vacuum Gripper**: Utilizes suction for reliable fruit picking of various shapes and sizes.

## 🧠 Control & Intelligence

- **Inverse Kinematics**: Specialized IK algorithm to handle singularities and improve path efficiency.
- **Open-loop control**: Used for simplified, cycle-based movement without feedback.
- **Forward/Inverse Kinematics**: Implemented with DH parameters and Jacobian-based velocity control.
- **Workspace Analysis**: Validated robot reach and effectiveness in 3D space.

## 🛠️ Simulation Environment

- **Platform**: ROS 2 (Galactic)
- **Simulation Tools**: Gazebo & RViz
- **CAD Models**: Designed in SolidWorks
- **Custom World**: Includes trees, plants, and crops
- **URDF**: Robot description integrates mobile base and manipulator

## 📊 Validation

- **FK/IK Validation**: Circular trajectory tracking in Z-X plane
- **Trajectory Visualization**: Plots in 2D and 3D
- **RViz & Gazebo**: Show full robot operation and environment

## 🎥 Demo Video

Watch the full simulation and functionality of Agrobot:  
[![Watch on YouTube](https://img.youtube.com/vi/gChkp6AioRo/0.jpg)](https://www.youtube.com/watch?v=gChkp6AioRo)

## 📌 Authors

- **Raghu Dharahas Reddy Kotla** 
- **Sai Dinesh Gelam** 

## 🚀 Future Work

- Integrate computer vision for fruit ripeness detection
- Implement SLAM for autonomous navigation
- Add real-time feedback using LiDAR & depth cameras
- Optimize singularity handling in IK
