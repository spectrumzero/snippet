cmake_minimum_required(VERSION 3.25.0)
project(PROJECT_NAME VERSION 1.0)

# specify the C standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# tell the compiler where to search the header files recursively.
include_directories("./")

add_executable(PROJECT_NAME "" "" )
