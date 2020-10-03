cmake_minimum_required(VERSION 2.8)
project(Astar)

add_definitions(-std=c++11)
#set(CMAKE_BUILD_TYPE Debug)

include_directories("include")

#add_library(libAstar src/main.cpp src/Astar.cpp)

add_executable(main src/main.cpp src/Astar.cpp)
#target_link_libraries(main libAstar)
