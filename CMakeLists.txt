cmake_minimum_required(VERSION 2.8.3)

project(susan_description)

find_package(catkin REQUIRED)

catkin_package()

find_package(roslaunch)

install(DIRECTORY launch meshes rviz urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
