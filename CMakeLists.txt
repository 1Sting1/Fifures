cmake_minimum_required(VERSION 3.25)
project(Figures)

set(CMAKE_CXX_STANDARD 17)

add_executable(Figures circl.cpp Abs.h main.cpp circl.h elips.cpp elips.h rectangle.cpp rectangle.h triangle.cpp triangle.h)
