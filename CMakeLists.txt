cmake_minimum_required(VERSION 3.20)

project(
    GameSmash
    VERSION 150426
    DESCRIPTION "A custom game engine"
    LANGUAGES CXX
)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_subdirectory(src)
add_subdirectory(samples)