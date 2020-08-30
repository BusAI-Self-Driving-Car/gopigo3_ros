# gopigo3_ros

ROS Implementation on Gopigo3 Robot.

## Book

- *Hands-On ROS for Robotics Programming*

## Dependencies

### 1. Basic

- [GoPiGo3 Raspberry Pi Firmware](https://github.com/DexterInd/GoPiGo3.git)
- [gopigo3_node](https://github.com/ros-gopigo/gopigo3_node.git)
- [XBox controller and Webcam](https://github.com/ros-gopigo/startup.git)
- [Robot description and Simulator](https://github.com/ros-gopigo3/gopigo3.git)

### 2. Lidar and SLAM Applications

- [rplidar_ros](https://github.com/Slamtec/rplidar_ros.git)
- [openslam_gmapping](https://github.com/ros-perception/openslam_gmapping.git)
- [slam_gmapping](https://github.com/ros-perception/slam_gmapping.git)
- [hector_slam](https://github.com/tu-darmstadt-ros-pkg/hector_slam.git)
- [slam_karto](https://github.com/ros-perception/slam_karto.git)
- [cartographer](https://github.com/cartographer-project/cartographer.git)
- [rplidar_slam](https://github.com/xpharry/rplidar_slam.git)

## Instruction

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

## Other Applications

- [How to run ROS navigation stack on GoPiGo3](https://github.com/iot-magi/gopigo3_navigation)
- [Turning Gopigo3 into an AWS IoT device](https://github.com/fold88/gopigo3)
- [Use Google Cloud Vision On the Raspberry Pi and GoPiGo](https://www.dexterindustries.com/howto/use-google-cloud-vision-on-the-raspberry-pi/)

## Reference

- [ROS Wiki: Robotsgopigo3](http://wiki.ros.org/Robots/gopigo3)
- [Browser Streaming Robot With The GoPiGo3](https://www.dexterindustries.com/GoPiGo/projects/python-examples-for-the-raspberry-pi/browser-video-streaming-robot-gopigo3/)
- [Starting with ROS on the GoPiGo3 and the Raspberry Pi](https://medium.com/robotics-with-ros/starting-with-ros-on-the-gopigo3-and-the-raspberry-pi-af62104d401e)
