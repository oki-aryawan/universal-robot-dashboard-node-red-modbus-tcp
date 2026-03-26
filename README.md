# UR3e Dashboard using Node-RED via Modbus TCP
This project provides a comprehensive Node-RED dashboard for monitoring and controlling the **Universal Robots UR3e** collaborative robot arm. The dashboard visualizes real-time robot data and enables intuitive control through a web-based interface connected via **Modbus TCP** protocol.

### Features
- **Joint Control & Monitoring**
  - Real-time monitoring of all 6 DOF (Degrees of Freedom) joint angles in degrees
  - Visual representation of joint positions and movements
- **TCP Movement Tracking**
  - TCP (Tool Center Point) position display in millimeters (mm)
  - 6-degree movement tracking (X, Y, Z position + 3-axis rotation)
- **Euler Angle Representation**
  - Automatic generation and display of Euler Angles for rotational components
  - Support for roll, pitch, and yaw visualization

## Tools Used
- **Node-RED**: Flow-based programming tool for IoT and industrial automation
- **Modbus TCP**: Communication protocol for reliable real-time data exchange with UR3e
- **Dashboard UI**: Node-RED dashboard nodes for interactive web-based interface
- **UR3e Robot**: Universal Robots collaborative manipulator arm
