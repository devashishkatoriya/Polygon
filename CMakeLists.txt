cmake_minimum_required(VERSION 3.6)
project(Polygon)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(Polygon ${SOURCE_FILES})

target_link_libraries(Polygon graph)