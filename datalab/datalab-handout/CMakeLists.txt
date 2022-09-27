cmake_minimum_required(VERSION 3.22)
project(datalab_handout C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(datalab_handout
        bits.c
        bits.h
        btest.c
        btest.h
        decl.c
        fshow.c
        ishow.c
        tests.c)
