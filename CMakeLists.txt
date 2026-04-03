# CMakeFiles.txt inside "RTClib" folder
cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "src/RTCx.cpp" 
                    INCLUDE_DIRS "src/." "."
                    REQUIRES "arduino" # Library requires Arduino
                    )

project(RTCx)