cmake_minimum_required(VERSION 3.13)

project(alloc3 C)

file(GLOB_RECURSE SOURCE_FILES src/*.h src/*.c)

add_executable(alloc3 ${SOURCE_FILES})