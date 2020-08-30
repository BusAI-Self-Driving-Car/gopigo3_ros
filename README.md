# gopigo3_ros
ROS Implementation on Gopigo3 Robot.

# Dependencies

- [GoPiGo3 Raspberry Pi Firmware](https://github.com/DexterInd/GoPiGo3.git)
- [gopigo3_node](https://github.com/ros-gopigo/gopigo3_node.git)
- [rplidar_ros](https://github.com/Slamtec/rplidar_ros.git)
- openslam_gmapping
- [slam_gmapping](https://github.com/ros-perception/slam_gmapping.git)
- rplidar_slam

# Instruction

**SLAM with gmapping**

Bring up robot and start gmapping in Gopigo3 robot side:

```
ssh pi@192.168.0.205
roslaunch gopigo3_ros gopigo3_slam_gmapping.launch
```

Launch rviz in Remote PC or Laptop:

```
roslaunch gopigo3_ros gopigo3_slam_rviz.launch
```

