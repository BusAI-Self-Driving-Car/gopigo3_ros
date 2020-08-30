# gopigo3_ros
ROS Implementation on Gopigo3 Robot.

# Dependencies

- [GoPiGo3 Raspberry Pi Firmware](https://github.com/DexterInd/GoPiGo3.git)
- [gopigo3_node](https://github.com/ros-gopigo/gopigo3_node.git)
- [rplidar_ros](https://github.com/Slamtec/rplidar_ros.git)
- [openslam_gmapping](https://github.com/ros-perception/openslam_gmapping.git)
- [slam_gmapping](https://github.com/ros-perception/slam_gmapping.git)
- [hector_slam](https://github.com/tu-darmstadt-ros-pkg/hector_slam.git)
- [slam_karto](https://github.com/ros-perception/slam_karto.git)
- [cartographer](https://github.com/cartographer-project/cartographer.git)
- [rplidar_slam](https://github.com/xpharry/rplidar_slam.git)

# Instruction

**Bring up Gopigo3**

```
ssh pi@robot_ip
roslaunch gopigo3_node gopigo3.launch
```

**SLAM with gmapping**

Start gmapping in Gopigo3 robot side:

```
ssh pi@robot_ip
roslaunch gopigo3_ros gopigo3_slam_gmapping.launch
```

Launch rviz in Remote PC or Laptop:

```
roslaunch gopigo3_ros gopigo3_slam_rviz.launch
```

