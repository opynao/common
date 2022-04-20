project(common)
cmake_minimum_required(VERSION 3.23)

set(CMAKE_CXX_STANDARD 20)

file(GLOB_RECURSE SRC_FILES ${CMAKE_CURRENT_SOURCE_DIR}/include/*.h)

add_library(${PROJECT_NAME}_lib ${SRC_FILES})
