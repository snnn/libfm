cmake_minimum_required (VERSION 2.6) 

if(WIN32)
add_definitions(-DUNICODE -D_UNICODE -DCOMPILER_MSVC -DNOMINMAX -D_CRT_SECURE_NO_WARNINGS)
endif()

ADD_SUBDIRECTORY(src)

