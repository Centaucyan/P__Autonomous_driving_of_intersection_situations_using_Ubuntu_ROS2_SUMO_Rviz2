# P__Autonomous_driving_of_intersection_situations_using_Ubuntu_ROS2_SUMO_Rviz2

## 1. Description
* SUMO(Simulation of Urban MObility)의 사용법을 익히고 경험해보고자 함.
* 이를 위해 ROS 2와 RViz 2를 연동하여 자율주행을 시뮬레이션해보는 개인 프로젝트.
---

## 2. Environment
* **OS:** Ubuntu 22.04
* **Language:** C++
* **Middle ware:** ROS2 Humble
* **Simulator:** SUMO(Simulation of Urban MObility)
* **Visualization Tool:** RViz2
---

## 3. Install
### 3.1. SUMO(Simulation of Urban MObility)
* **Reference site:** https://sumo.dlr.de/docs/Installing/index.html
* sudo add-apt-repository ppa:sumo/stable
* sudo apt update
* sudo apt install sumo sumo-tools sumo-doc
* echo "export SUMO_HOME=/usr/share/sumo" >> ~/.bashrc
* source ~/.bashrc
---