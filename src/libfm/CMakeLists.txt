cmake_minimum_required (VERSION 2.6) 

#add_definitions(-DFM_FLOAT=double)

file(GLOB SRC_HEADERS
    "src/*.h"
)
add_executable( libfm libfm.cpp ${SRC_HEADERS})