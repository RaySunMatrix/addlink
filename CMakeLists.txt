cmake_minimum_required(VERSION 3.28)
project(addlink)

set(CMAKE_CXX_STANDARD 17)

add_executable(addlink app.cpp
        international.cc
        src/main.cc)
