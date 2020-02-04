cmake_minimum_required(VERSION 3.5)
#include($ENV{IDF_PATH}/tools/cmake/project.cmake)
include(/home/vad/esp/esp-idf/tools/cmake/project.cmake)
set(PROJECT_NAME Internet_of_Things_Projects_with_ESP32)
project(${PROJECT_NAME})

add_subdirectory(Chapter01/blinking)
