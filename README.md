# P__Autonomous_driving_of_intersection_situations_using_Ubuntu_ROS2_SUMO_Rviz2

## 1. Description
* SUMO(Simulation of Urban MObility)의 사용법을 익히고 경험해보고자 함.
* SUMO와 ROS2, RViz2를 연동하여 자율주행 시뮬레이션을 위한 개인 프로젝트.
---

## 2. Environment
* **OS:** Ubuntu 22.04 LTS(Jammy Jellyfish)
* **Language:** C++, Python(ver: 3.12.13)
* **Middle ware:** ROS2 Humble
* **Simulator:** SUMO(ver: 1.27.1)
* **Visualization Tool:** RViz2
---

## 3. Reference
* **Install:** https://sumo.dlr.de/docs/Installing/index.html
* **Git:** https://github.com/eclipse-sumo/sumo.git
---

## 4. Install
### 4.1. SUMO(Simulation of Urban MObility)
* sudo add-apt-repository ppa:sumo/stable
* sudo apt update
* sudo apt install sumo sumo-tools sumo-doc
* echo "export SUMO_HOME=/usr/share/sumo" >> ~/.bashrc
* source ~/.bashrc
---