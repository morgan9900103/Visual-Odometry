cmake_minimum_required(VERSION 2.6)
project(project)

add_executable(project main.cpp)

install(TARGETS project RUNTIME DESTINATION bin)
