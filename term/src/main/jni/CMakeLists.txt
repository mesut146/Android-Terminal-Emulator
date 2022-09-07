cmake_minimum_required(VERSION 3.4.1)

set(src common.cpp fileCompat.cpp termExec.cpp)
add_library(libjackpal-androidterm5 SHARED ${src})


target_link_libraries(libjackpal-androidterm5 log)