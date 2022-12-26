cmake_minimum_required(VERSION 3.13)

project(cmake_test)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}" -std=c++1y)

file(GLOB 
    CPPS "*.cpp")


add_executable(${PROJECT_NAME} ${CPPS})