# ROS2

## 22.04 

ROS2: OK.
ardupilot
mavlink
gazebo
gz sim
Win: XLaunch


## Build from source Ubuntu 20.04 ... humble ...

Some residual old packages etc. from ROS1 ...  perhaps
It needs a clean U20.04

Installation, troubleshooting, tests, experience, ... with ROS2 - Robot Operating System

WSL2

source ~/ros2-src/install/setup.bash
export ROS_MASTER_URI=http://172.23.224.1:11311
export ROS_IP=http://172.23.224.1

?

rviz 

network bridge ...

https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html

source /opt/ros/humble/setup.bash
export DISPLAY=$(awk '/nameserver / {print $2; exit}' /etc/resolv.conf 2>/dev/null):0


