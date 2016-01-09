cmake_minimum_required(VERSION 2.8)

file(GLOB helloworld_CSRC
    "*.c"
    "*.h"
)

file(GLOB helloworld_CPPSRC
    "*.cpp"
    "*.h"
)
add_executable(hello ${helloworld_CPPSRC} ${helloworld_CSRC})