cmake_minimum_required (VERSION 2.6)
project (travis_cmake_gcc_cpp17)
add_executable(travis_cmake_gcc_cpp17 main.cpp)

set_property(TARGET travis_cmake_gcc_cpp11 PROPERTY CXX_STANDARD 17)
set_property(TARGET travis_cmake_gcc_cpp11 PROPERTY CXX_STANDARD_REQUIRED ON)