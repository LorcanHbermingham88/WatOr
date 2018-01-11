cmake_minimum_required(VERSION 3.8)
project(Wator)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
    cmake-build-debug/cmake_install.cmake
    cmake-build-debug/CMakeCache.txt
        cmake-build-debug/Makefile
        CMakeLists.txt
    creature.cpp
    creature.h
    main.cpp)

add_executable(Wator ${SOURCE_FILES})