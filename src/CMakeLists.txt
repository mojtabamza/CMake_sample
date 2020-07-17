project(cmake_prj)
cmake_minimum_required(VERSION 3.5)

set(CMAKE_CXX_STANDARD 14)

add_library(tools	max_lib/max.cpp
			min_lib/min.cpp)

add_executable(cmake_prj	main.cpp)

target_link_libraries(cmake_prj	tools)

