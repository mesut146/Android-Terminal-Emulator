cmake_minimum_required(VERSION 3.4.1)

set(src process.cpp)
add_library(jackpal-termexec2 SHARED ${src})


target_link_libraries(jackpal-termexec2 log c)