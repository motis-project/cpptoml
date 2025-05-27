cmake_minimum_required(VERSION 3.10)
project(cpptoml)

add_library(cpptoml INTERFACE)
target_include_directories(cpptoml SYSTEM INTERFACE include)
