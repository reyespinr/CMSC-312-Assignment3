cmake_minimum_required(VERSION 3.16)
project(CMSC-312-Assignment2)

set(CMAKE_CXX_STANDARD 20) # Ensure C++20 is used

include_directories(include)

# Executable for part 1 of the assignment
add_executable(Part1 src/part1.cpp src/reader_writer.cpp)
