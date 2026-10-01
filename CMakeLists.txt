cmake_minimum_required(VERSION 3.15)
set(PROJECT_NAME "app")
project(${PROJECT_NAME})
add_executable(${PROJECT_NAME} src/main.cpp)
target_sources(
    ${PROJECT_NAME}
    PRIVATE
    src/main.cpp
    )

target_include_directories(
    ${PROJECT_NAME}
    PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}/include
    ) 


