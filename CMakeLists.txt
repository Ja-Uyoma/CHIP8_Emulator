cmake_minimum_required(VERSION 3.20)

project("CHIP-8 Emulator"
    VERSION 0.1.1
    DESCRIPTION "An interpreter for the CHIP-8 virtual machine"
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_EXPORT_COMPILE_COMMANDS TRUE)

add_subdirectory(src)