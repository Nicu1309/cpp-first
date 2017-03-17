cmake_minimum_required(VERSION 3.6)
project(cpp_first)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES library.cpp library.h)
add_library(cpp_first ${SOURCE_FILES})