cmake_minimum_required(VERSION 3.16)

project(ListFastAllocator)

add_library(ListFastAllocatorLib listfastalloc.cpp)
add_executable(ListFastAllocatorPlay listfastalloc_play.cpp)
target_link_libraries(ListFastAllocatorPlay ListFastAllocatorLib)