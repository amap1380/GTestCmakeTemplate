cmake_minimum_required(VERSION 3.10)

project(Project CXX)
set(CMAKE_CXX_STANDARD 17)

enable_testing()

add_subdirectory(lib)
add_subdirectory(src)
add_subdirectory(test)
