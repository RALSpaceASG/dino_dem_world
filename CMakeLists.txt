cmake_minimum_required(VERSION 2.8.3)
project(dino_dem_world)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch models worlds
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

