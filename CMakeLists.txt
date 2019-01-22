cmake_minimum_required(VERSION 3.6)
project(TerarkSQLBenchmark)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(TerarkSQLBenchmark ${SOURCE_FILES})