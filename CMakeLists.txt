cmake_minimum_required(VERSION 3.22.1)

#set(CMAKE_BUILD_TYPE Debug)

project(Homework)

set(CMAKE_CXX_STANDART 11)

file(GLOB CPPS "*.cpp")

add_executable(${PROJECT_NAME} ${CPPS})