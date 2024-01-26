cmake_minimum_required(VERSION 2.8.3)
project(pioneer3dx_description)

find_package(catkin REQUIRED COMPONENTS
  geometry_msgs
  sensor_msgs
  std_msgs
  robot_state_publisher
  urdf
)

catkin_package(CATKIN_DEPENDS
  robot_state_publisher
  urdf
  geometry_msgs
  sensor_msgs
  std_msgs
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
