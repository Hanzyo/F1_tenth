cmake_minimum_required(VERSION 3.0.2)
project(vicon_control)

find_package(catkin REQUIRED COMPONENTS
  cv_bridge
  roscpp
  rospy
  sensor_msgs
  std_msgs
  tf
)

catkin_package(
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)


