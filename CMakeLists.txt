cmake_minimum_required(VERSION 3.13.4)

set(CMAKE_CXX_STANDARD 20)

project(libjson)
add_library(${PROJECT_NAME} 
    include/${PROJECT_NAME}/deserializable.h
    include/${PROJECT_NAME}/object.h)

target_include_directories(${PROJECT_NAME} PUBLIC include)