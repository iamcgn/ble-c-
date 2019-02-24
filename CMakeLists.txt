cmake_minimum_required(VERSION 3.13)
project(ble_c__)

set(CMAKE_CXX_STANDARD 17)

find_package(sdbus-c++ REQUIRED)

add_library(ble_c__ SHARED library.cpp library.h)