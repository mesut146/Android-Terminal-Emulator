cmake_minimum_required(VERSION 3.4.1)

set(src process.cpp)
add_library(libjackpal-termexec2 SHARED ${src})


target_link_libraries(libjackpal-termexec2 log c)