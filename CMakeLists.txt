cmake_minimum_required(VERSION 3.8)
project(Exercise_7_BigO)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        sort_functions.c
        sort_functions.h
        sort_main.c)

add_executable(Exercise_7_BigO ${SOURCE_FILES})