cmake_minimum_required(VERSION 3.26)
project(DesignPatterns)

set(CMAKE_CXX_STANDARD 14)

set(CMAKE_EXE_LINKER_FLAGS "-static-libgcc -static-libstdc++")

add_subdirectory(Adapter)
add_subdirectory(Command)

add_executable(main main.cpp
        main.cpp)
