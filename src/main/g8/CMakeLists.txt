cmake_minimum_required (VERSION 3.3)

project ($name$)

add_executable($name$ src/main.cpp)

target_compile_features($name$ PUBLIC cxx_std_11)
