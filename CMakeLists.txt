cmake_minimum_required(VERSION 3.20)
project(L1_IA2001)

set(CMAKE_CXX_STANDARD 14)

add_executable(L1_IA2001 main.cpp Game.cpp Game.h Character.cpp Character.h Item.cpp Item.h Enemy.cpp Enemy.h Fight.cpp Fight.h)
