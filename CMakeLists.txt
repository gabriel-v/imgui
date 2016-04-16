cmake_minimum_required (VERSION 2.8)
project(imgui)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
        imconfig.h
        imgui.cpp
        imgui.h
        imgui_demo.cpp
        imgui_draw.cpp
        imgui_internal.h
        stb_rect_pack.h
        stb_textedit.h
        stb_truetype.h
        )

add_library(imgui ${SOURCE_FILES})