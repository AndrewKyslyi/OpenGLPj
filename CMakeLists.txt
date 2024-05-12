cmake_minimum_required(VERSION 3.29 FATAL_ERROR)

project(OpenGLPj)

add_executable(OpenGLPj src/main.cpp)

add_subdirectory(external/glfw)
