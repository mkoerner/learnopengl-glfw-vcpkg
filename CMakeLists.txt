cmake_minimum_required(VERSION 3.19)

project(glfw-example CXX)

find_package(glfw3 REQUIRED)
find_package(glad REQUIRED)

add_executable(glfw-example main.cpp)
target_compile_features(glfw-example PRIVATE cxx_std_20)

target_link_libraries(glfw-example
  PRIVATE
    glfw
    glad::glad)
