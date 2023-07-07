cmake_minimum_required(VERSION 3.15)

project(simple)

set(CMAKE_CXX_STANDARD 23)

add_executable(simple main.cpp)

target_link_libraries(simple PUBLIC plassfilec)
target_include_directories(simple PUBLIC ../../src/plassfilec)