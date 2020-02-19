cmake_minimum_required(VERSION 3.15)
project(thermoprop)

set(CMAKE_CXX_STANDARD 14)

add_library(thermoprop SHARED library.cpp library.h)