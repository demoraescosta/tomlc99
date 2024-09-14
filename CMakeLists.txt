project(tomlc99)

add_library(tomlc99 toml.h toml.c)
target_include_directories(tomlc99 PUBLIC ./)