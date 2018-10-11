cmake_minimum_required(VERSION 3.8)
project(datalab_cs33_handout)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        bits.c
        bits.h
        btest.c
        btest.h
        decl.c
        fshow.c
        ishow.c
        tests.c)

add_executable(datalab_cs33_handout ${SOURCE_FILES})