# ROS Robot Walker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Project overview
Roomba vacuum cleaner robot like implementation on turtlebot by avoiding obstacles in space.

## Dependencies

This ROS node is made to be used on systems which have:

    ROS Kinetic
    Ubuntu 16.04
    gazebo_ros 

##  Build
```
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/
catkin_make
source devel/setup.bash
cd src/
git clone --recursive https://github.com/kartikmadhira1/RL_HW3
cd ..
catkin_make
```
## Run demo
In order to launch the turtlebot simulation, type the command below:

```
roslaunch robot_walker robot_walker.launch

```
