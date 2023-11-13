cmake_minimum_required(VERSION 3.23)
project(C___project)

set(CMAKE_CXX_STANDARD 20)

add_executable(C___project virtual-cricket-game.cpp player.h player.cpp team.h team.cpp game.h game.cpp)
