cmake_minimum_required(VERSION 2.8.3)
project(hello_appveyor)


set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

add_subdirectory (src)
