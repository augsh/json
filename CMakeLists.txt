cmake_minimum_required(VERSION 3.20)

project(json)

add_library(${PROJECT_NAME} INTERFACE IMPORTED GLOBAL)
target_include_directories(${PROJECT_NAME} INTERFACE include)
