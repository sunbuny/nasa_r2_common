cmake_minimum_required(VERSION 2.8.3)
project(r2_moveit_config)

find_package(catkin REQUIRED COMPONENTS r2_gazebo)

catkin_package()

install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY config DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
