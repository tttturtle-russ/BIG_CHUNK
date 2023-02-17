cmake_minimum_required(VERSION 3.24)
project(DDoS_detection C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(DDoS_detection
        detection.c
        detection.h)
