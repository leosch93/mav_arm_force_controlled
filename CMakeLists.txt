cmake_minimum_required(VERSION 2.8.3)
project(mav_arm_force_controlled)

find_package(catkin_simple REQUIRED)
catkin_simple(ALL_DEPS_REQUIRED)

add_definitions(-std=c++11)

#############
# LIBRARIES #
#############
#cs_add_library(${PROJECT_NAME}
#        src/framework_processor.cpp)

############
# BINARIES #
############
#cs_add_executable(state_publisher
#  src/state_publisher.cpp)
#target_link_libraries(state_publisher ${catkin_LIBRARIES})

##########
# EXPORT #
##########
cs_install()
cs_export()
