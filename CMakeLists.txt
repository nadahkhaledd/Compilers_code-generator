cmake_minimum_required(VERSION 3.21)
project(a1)

set(CMAKE_CXX_STANDARD 14)
set(SOURCE ${CMAKE_CURRENT_SOURCE_DIR}/input.txt)

add_executable(a1 main.cpp ${SOURCE})
