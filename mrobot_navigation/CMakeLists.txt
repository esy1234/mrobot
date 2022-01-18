cmake_minimum_required(VERSION 3.0.2)
project(mrobot_navigation)

find_package(catkin REQUIRED COMPONENTS
  gmapping
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES mrobot_navigation
#  CATKIN_DEPENDS gmapping
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)

