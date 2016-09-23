cmake_minimum_required(VERSION 3.6)
project(Professional)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++1y")

set(SOURCE_FILES UserInterface.cpp Employee.cpp Employee.h Database.cpp Database.h)
add_executable(Professional ${SOURCE_FILES})
