cmake_minimum_required(VERSION 3.22.1)

project(kernel-project)

set(CMAKE_CXX_STANDARD 11.4.0)

add_executable(kernel kernel.cpp)

target_include_directories(kernel PRIVATE )