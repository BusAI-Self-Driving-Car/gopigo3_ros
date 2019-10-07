cmake_minimum_required(VERSION 2.8.3)
project(gopigo3_ros)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rosconsole
  sensor_msgs
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

catkin_package()

