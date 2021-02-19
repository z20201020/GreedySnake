cmake_minimum_required(VERSION 3.17)
project(GreedySnake)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(GreedySnake
        src/code/controller.cpp
        src/header/controller.h
        src/code/food.cpp
        src/header/food.h
        src/code/main.cpp
        src/code/map.cpp
        src/header/map.h
        src/code/point.cpp
        src/header/point.h
        src/code/snake.cpp
        src/header/snake.h
        src/code/startinterface.cpp
        src/header/startinterface.h
        src/code/tools.cpp
        src/header/tools.h)
