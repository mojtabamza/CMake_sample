project(cmake_prj)
cmake_minimum_required(VERSION 3.5)


set(EXECUTABLE_OUTPUT_PATH	${PROJECT_SOURCE_DIR}/bin)
set(LIBRARY_OUTPUT_PATH		${PROJECT_SOURCE_DIR}/lib)

include_directories(${PROJECT_SOURCE_DIR}/src)
add_subdirectory(${PROJECT_SOURCE_DIR}/src)


