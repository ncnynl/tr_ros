cmake_minimum_required(VERSION 2.8.3)
project(tr_teleop)

find_package(catkin REQUIRED)

catkin_package()

catkin_install_python(PROGRAMS nodes/tr_teleop_joy
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})
