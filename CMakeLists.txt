cmake_minimum_required(VERSION 3.8)
project(untitled1)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp creature.cpp creature.h)
add_library(untitled1 ${SOURCE_FILES})