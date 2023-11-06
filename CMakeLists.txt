cmake_minimum_required(VERSION 3.26)
project(JoyRec)

set(CMAKE_CXX_STANDARD 11)

add_executable(JoyRec c11/src/main.cpp
        c11/include/Numeric.hpp
        test/c11/test_numeric_tensor.cpp)
