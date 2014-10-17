cmake_minimum_required(VERSION 2.8.3)
project(project_launch)

# Get the information about this package's buildtime dependencies
find_package(catkin REQUIRED COMPONENTS
)

# Declare that this catkin package's runtime dependencies
catkin_package()

include_directories(include ${catkin_INCLUDE_DIRS})