cmake_minimum_required(VERSION 3.3)
project(Programming_Languages)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES driver.cpp lexer.h lexer.cpp)
add_executable(Programming_Languages ${SOURCE_FILES})