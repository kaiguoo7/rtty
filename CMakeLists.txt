cmake_minimum_required(VERSION 2.8)

project(rtty C)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake/Modules/")

#set(CMAKE_VERBOSE_MAKEFILE ON)

add_subdirectory(src)
