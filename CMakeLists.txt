cmake_minimum_required(VERSION 2.8)

file(GLOB helloworld_CPPSRC
    "*.cpp"
    "*.h"
)
file(GLOB helloworld_CSRC
    "*.c"
    "*.h"
)

add_executable(hello ${helloworld_CSRC} ${helloworld_CPPSRC})