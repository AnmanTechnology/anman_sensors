cmake_minimum_required(VERSION 2.8.3)
project(anman_sensors)

find_package(catkin REQUIRED COMPONENTS
  urdf
  xacro
)

catkin_package()

install(
  DIRECTORY actuators gazebo_model sensors
  DESTINATION ${CATKIN_PACKAGE_INCLUDE_DESTINATION}
)
