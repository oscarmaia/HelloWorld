cmake_minimum_required(VERSION 3.25)

project(hello VERSION 0.1.0 LANGUAGES C CXX)

add_subdirectory(raylib)

add_executable(hello main.cpp)

target_link_libraries(hello raylib)