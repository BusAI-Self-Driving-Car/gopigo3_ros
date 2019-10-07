# gopigo3_ros
ROS Implementation on Gopigo3 Robot.

# Dependencies

- gopigo3_node
- rplidar_ros
- openslam_gmapping
- slam_gmapping
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

