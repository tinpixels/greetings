cmake_minimum_required(VERSION 3.6)
project(greetings)

include_directories(/usr/local/Cellar/allegro/5.2.2/include/allegro5)
include_directories(/usr/local/Cellar/)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c)
add_executable(greetings ${SOURCE_FILES})