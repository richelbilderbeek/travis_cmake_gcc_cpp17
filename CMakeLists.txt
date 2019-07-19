cmake_minimum_required (VERSION 2.6)
add_executable(travis_cmake_gcc_cpp17 main.cpp)

# C++17
set_property(TARGET travis_cmake_gcc_cpp17 PROPERTY CXX_STANDARD 17)
set_property(TARGET travis_cmake_gcc_cpp17 PROPERTY CXX_STANDARD_REQUIRED ON)