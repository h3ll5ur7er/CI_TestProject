cmake_minimum_required(VERSION 2.8)

file(GLOB helloworld_SRC
    "*.cpp"
    "*.c"
    "*.h"
)

add_executable(hello ${helloworld_SRC})