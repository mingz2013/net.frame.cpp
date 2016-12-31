cmake_minimum_required(VERSION 3.3)
project(server_base)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
        Server.cpp Server.h main.cpp)

add_executable(server_base ${SOURCE_FILES} Server.cpp Server.h)