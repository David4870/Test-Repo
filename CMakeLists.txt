cmake_minimum_required(VERSION 3.28.1)

project(Test)

add_executable(${PROJECT_NAME} main.cpp)

set(SDL_TEST OFF)
set(SDL_TEST_LIBRARY OFF)

add_subdirectory(external/SDL)