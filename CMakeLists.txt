cmake_minimum_required(VERSION 3.10)

project(glad2)

add_library(glad2 "opengl-4.6-core/src/gl.c")
target_include_directories(glad2 PUBLIC "opengl-4.6-core/include")
