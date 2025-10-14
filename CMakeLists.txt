cmake_minimum_required(VERSION 3.10)
project(HelloWorldApp)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_EXE_LINKER_FLAGS "-static-libstdc++ -static-libgcc")

add_executable(HelloWorldApp main.cpp)
