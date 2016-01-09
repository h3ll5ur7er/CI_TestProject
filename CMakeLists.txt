cmake_minimum_required(VERSION 2.8)

file(GLOB helloworld_HEADERS
    "*.h"
)

file(GLOB helloworld_CSRC
    "*.c*"
)

add_executable(hello ${helloworld_CSRC})