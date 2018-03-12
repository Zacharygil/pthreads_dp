cmake_minimum_required(VERSION 3.6)
project(pthreads_dp)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
    dining_philosophers.c
    dp_asymmetric.c
    dp_waiter.c
    Makefile)

add_executable(pthreads_dp ${SOURCE_FILES})