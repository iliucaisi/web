cmake_minimum_required(VERSION 3.9)
# project name
project(add)

# head file path
include_directories(
#        include
)

# source directory
# aux_source_directory(src DIR_SRCS)

# set environment variable
set(CMAKE_CXX_STANDARD 11)

# add executable file
add_executable(add add.cpp)

# add link library
# target_link_libraries(../bin/bin m)