cmake_minimum_required(VERSION 3.16)

# set the project name and version
project(LearnCmake VERSION 0.0.1)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(hello ./src/main.cpp)