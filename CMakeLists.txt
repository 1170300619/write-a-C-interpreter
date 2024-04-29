cmake_minimum_required(VERSION 3.17)
project(my_C_interpreter C)

set(CMAKE_C_STANDARD 11)

add_executable(my_C_interpreter main.c
        hello.c
        my-C-interpreter.c
        xc.c
        xc-tutor.c)
