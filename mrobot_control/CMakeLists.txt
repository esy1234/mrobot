cmake_minimum_required(VERSION 3.0.2)
project(mrobot_control)

find_package(catkin REQUIRED COMPONENTS
  controller_manager
  joint_state_controller
  robot_state_publisher
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES mrobot_control
#  CATKIN_DEPENDS controller_manager joint_state_controller robot_state_publisher
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
