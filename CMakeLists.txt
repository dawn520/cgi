cmake_minimum_required(VERSION 3.8)
project(cgi)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c user.c)
add_executable(cgi ${SOURCE_FILES})