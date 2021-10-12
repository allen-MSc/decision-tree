cmake_minimum_required(VERSION 3.19)
project(cs_data_structures)

set(CMAKE_CXX_STANDARD 14)

file(COPY iris.txt DESTINATION ${CMAKE_BINARY_DIR})

add_executable(decision-tree main.cpp)

