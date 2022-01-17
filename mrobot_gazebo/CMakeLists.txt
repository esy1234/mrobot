cmake_minimum_required(VERSION 3.0.2)
project(mrobot_gazebo)

find_package(catkin REQUIRED COMPONENTS
  gazebo_plugins
  gazebo_ros
  gazebo_ros_control
  mrobot_description
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES mrobot_gazebo
  CATKIN_DEPENDS
    gazebo_ros
    mrobot_description
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)

