cmake_minimum_required(VERSION 3.16)
project(Minesweeper_Cpp)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_executable(Minesweeper_Cpp
        src/Agent.hpp
        src/Main.cpp
        src/ManualAI.hpp
        src/MyAI.cpp
        src/MyAI.hpp
        src/RandomAI.hpp
        src/World.cpp
        src/World.hpp)
