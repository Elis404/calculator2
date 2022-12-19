cmake_minimum_required(VERSION 3.23)
project(calculator2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(tests)

add_executable(calculator2
        tests/doctest.h
        tests/Tests.cpp
        calculator.cpp
        calculator.h)
