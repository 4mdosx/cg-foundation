cmake_minimum_required (VERSION 3.10)
project (homework0)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})

find_package(Eigen3 REQUIRED)

add_executable (main main.cpp)
target_link_libraries(main Eigen3::Eigen)
