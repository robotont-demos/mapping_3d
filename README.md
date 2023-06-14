# 3D mapping
This repository is a ROS package that contains 3D mapping demo showing the capabilities of the Robotont platform create a 3D map of the surrounding using different methods.

## Prerequisites on Robotont on-board computer
 * [RTAB-Map ROS Wrapper](http://wiki.ros.org/rtabmap)

This dependency can be obtained from apt by entering the following commands:

```bash
sudo apt update
sudo apt install ros-noetic-rtabmap-ros
```

## Launching the demo
**On Robotont on-board computer**, launch 3d_mapping.launch<br/>
```bash
roslaunch mapping_3d 3d_mapping.launch
```

**On PC**, launch 3d_mapping_display.launch to visualize the result<br/>

```bash
roslaunch mapping_3d 3d_mapping_display.launch
```