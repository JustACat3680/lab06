cmake_minimum_required(VERSION 3.31)
set(CMAKE_CXX_STANDARD 17)
project(solver)
add_executable(solver equation.cpp)
target_link_libraries(solver PRIVATE solver_lib formatter_ex)

