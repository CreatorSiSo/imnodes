cmake_minimum_required(VERSION 3.0)

project(imnodes)

# Targets
add_library(
  ${PROJECT_NAME} STATIC ./imnodes.cpp)

# Includes
target_include_directories(${PROJECT_NAME} PRIVATE ./ PUBLIC ../imgui)
