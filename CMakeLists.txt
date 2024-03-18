cmake_minimum_required(VERSION 3.27)
project(CLION)

set(CMAKE_CXX_STANDARD 17)

# Set architecture for macOS
set(CMAKE_OSX_ARCHITECTURES "arm64" CACHE STRING "Build architecture for macOS")

add_executable(CLION main.cpp abb.o arbin.o nodoB.o)
