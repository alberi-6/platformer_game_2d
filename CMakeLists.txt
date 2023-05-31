cmake_minimum_required(VERSION 3.0.0)
project(platformer_2D VERSION 0.1.0)

add_executable(platformer_2D main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
