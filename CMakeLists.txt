cmake_minimum_required(VERSION 3.10)

# Set the project name and version
project(MyProject VERSION 1.0)

# Set the C standard
set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED True)

# Add the source files
set(SOURCE_FILES add.c average.c)

# Add an executable target
add_executable(MyExecutable ${SOURCE_FILES})
