cmake_minimum_required(VERSION 3.18.3)
project(chr-mem)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON)

add_library(chr-mem src/chr-mem)
set_target_properties(chr-mem PROPERTIES LINKER_LANGUAGE CXX)

target_include_directories(chr-mem PUBLIC src/)

add_subdirectory(src)