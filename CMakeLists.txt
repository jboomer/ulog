cmake_minimum_required(VERSION 3.5)
project(ulog)

set(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -DULOG_ENABLED")

add_subdirectory(tests)
add_subdirectory(src)
