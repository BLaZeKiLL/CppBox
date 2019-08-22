cmake_minimum_required (VERSION 2.6)
project (CppBox)

set(CMAKE_BINARY_DIR ..)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_executable(Main src/main.cpp)