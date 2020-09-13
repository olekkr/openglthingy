cmake_minimum_required(VERSION 3.12)
project(openglthingy VERSION 1.0.0)

add_library(
    GLFW
    libs/glfw/include/GLFW/glfw3.h

)



set_target_properties(GLFW PROPERTIES LINKER_LANGUAGE CXX)

add_executable(main src/main.cpp)