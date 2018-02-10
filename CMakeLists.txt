cmake_minimum_required(VERSION 3.6)

create_static_library(
    TARGET
        hydrogen
    SOURCES
        hydrogen.c
    INCLUDE_DIRS
        .
    LIBRARIES
)
