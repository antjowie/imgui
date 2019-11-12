cmake_minimum_required(VERSION 3.1)

project (imgui VERSION 1.0
               LANGUAGES CXX
)

add_library(imgui INTERFACE)

target_include_directories(imgui INTERFACE /)