cmake_minimum_required(VERSION 3.0.2)
project(cpr_indoornav_husky)

find_package(catkin REQUIRED)

catkin_package(
)

include_directories(
)

install(PROGRAMS
  scripts/environment
  scripts/husky_power_monitor
  scripts/husky_safety_stop
  scripts/install
  scripts/start_husky_bridge

  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)

install(DIRECTORY config img launch urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
