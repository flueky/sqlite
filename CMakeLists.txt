cmake_minimum_required(VERSION 3.8)
project(sqlite)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES shell.c sqlite3.c sqlite3.h sqlite3ext.h)
add_executable(sqlite ${SOURCE_FILES})