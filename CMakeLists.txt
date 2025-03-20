cmake_minimum_required(VERSION 3.30)
project(sandbox)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
add_executable(sandbox 
  src/main.cpp
)

set(CMAKE_EXPORT_COMPILE_COMMANDS TRUE)
