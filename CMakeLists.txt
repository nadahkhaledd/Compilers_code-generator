cmake_minimum_required(VERSION 3.21)
project(a1)

set(CMAKE_CXX_STANDARD 14)
set(SOURCE ${CMAKE_CURRENT_SOURCE_DIR}/input.txt ${CMAKE_CURRENT_SOURCE_DIR}/output.txt ${CMAKE_CURRENT_SOURCE_DIR}/debug.txt)

add_executable(a1 main.cpp ${SOURCE})
