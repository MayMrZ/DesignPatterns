cmake_minimum_required(VERSION 3.26)
project(Adapter)

set(CMAKE_CXX_STANDARD 14)

set(CMAKE_EXE_LINKER_FLAGS "-static-libgcc -static-libstdc++")

add_executable(Adapter Adapter.cpp)
