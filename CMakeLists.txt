cmake_minimum_required(VERSION 3.5)
add_definitions(-std=c++17)
add_executable(planner cost.cpp  cost.h  main.cpp  road.cpp  road.h  vehicle.cpp  vehicle.h)
