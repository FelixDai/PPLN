cmake_minimum_required(VERSION 3.1)
project(chap1)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(chap1
        ch1.cpp
        ch1.h
        ch1_main.cpp)
