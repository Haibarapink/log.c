cmake_minimum_required(VERSION 3.22)
project(log_cpp)

set(CMAKE_CXX_STANDARD 11)

include_directories(src)

add_executable(log_cpp
        example/example.cc
        src/log.hpp)
