# Specify the minimum version of CMake required to build the project
cmake_minimum_required(VERSION 3.10)

# Set the project name
project(MyProject)

# Set the C standard
set(CMAKE_C_STANDARD 11)

# Add the source files
set(SOURCE_FILES add.c average.c)

# Add an executable target
add_executable(MyExecutable ${SOURCE_FILES})
