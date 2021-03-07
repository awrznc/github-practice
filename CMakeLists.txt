cmake_minimum_required(VERSION 3.17)
project(project C)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)
add_executable(sample ${CMAKE_CURRENT_SOURCE_DIR}/main.c)
