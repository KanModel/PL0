cmake_minimum_required(VERSION 3.12)
project(PL0 C)

set(CMAKE_CXX_STANDARD 11)

include_directories(.)

add_executable(PL0
        pl0.c
        pl0.h)
