cmake_minimum_required(VERSION 3.13)
project(MyCodeExamples)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(examples/arrays)
add_subdirectory(examples/classes)
add_subdirectory(examples/inheritance)
add_subdirectory(examples/strings)
add_subdirectory(examples/vector)

add_executable(main main.cpp)



