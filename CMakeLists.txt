cmake_minimum_required (VERSION 2.8)
set(PROJECT http-parser)

project(${PROJECT} C )

option(CXX11 "Force C++11 compiler" "OFF")

include_directories( "." )

set(PROJECT_SRC_GLOBS "http_parser.c" )

set(PROJECT_INCLUDES_GLOBS "http_parser.h" )

INCLUDE (common.cmake)

