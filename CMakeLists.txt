cmake_minimum_required(VERSION 3.11.0)
project(cpp_uservice_playground)

set(CMAKE_CXX_STANDARD 14)
# Specifying the build directory is not working, I don't know why
set(PROJECT_BINARY_DIR build)

add_executable(cpp-uservice
        README.md src/main.cpp)
