cmake_minimum_required(VERSION 3.15)
project(SimpleDB)

set(CMAKE_CXX_STANDARD 14)

add_executable(
        SimpleDB
        LICENSE
        README.md
        src/simpledb.c
        src/simpledb.h
        )
