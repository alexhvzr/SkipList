cmake_minimum_required(VERSION 3.13)
project(SkipList)

set(CMAKE_CXX_STANDARD 14)

add_executable(SkipList main.cpp slist.h slist.cpp.h statistics.cpp)