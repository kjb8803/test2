cmake_minimum_required (VERSION 2.8) 

project (Test)

#SET(CMAKE_C_COMPILER C:/MinGW/bin/gcc)
#SET(CMAKE_CXX_COMPILER C:/MinGW/bin/g++)
SET(CMAKE_C_COMPILER "gcc")
SET(CMAKE_CXX_COMPILER "g++")

ADD_EXECUTABLE (test2.out test.cpp)
