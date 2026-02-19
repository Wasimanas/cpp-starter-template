cmake_minimum_required(VERSION 3.15)
set(PROJECT_NAME "api")
project(${PROJECT_NAME})
add_executable(api main.cpp)
target_include_directories(
    ${PROJECT_NAME}
    PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}/include
    ) 


