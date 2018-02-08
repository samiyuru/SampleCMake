cmake_minimum_required(VERSION 2.8)
project(SampleMakefile)

set(CMAKE_CXX_STANDARD 11)

add_executable(main
        Author.h
        Book.cpp
        Book.h
        Main.cpp
)
