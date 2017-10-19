

cmake_minimum_required(VERSION 3.4.1)



set(root './')

include_directories("include" "src" "${root}")
file(GLOB darknet_src src/*.c src/*.cpp)
add_library(darknet ${darknet_src})

