cmake_minimum_required(VERSION 3.1)

project(myProject)

# commenting these two lines makes intellisense work correctly
set(CMAKE_C_STANDARD            "99")
set(CMAKE_C_STANDARD_REQUIRED   "ON")

# alternatively, commenting the cmain executable makes intellisense work correctly
add_executable(cmain main.c)
add_executable(cxxmain main.cpp)
