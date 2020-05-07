cmake_minimum_required (VERSION 2.6)
project (h264NaluAnalyzer)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")

add_subdirectory(tools)
add_subdirectory(ldecod)
add_subdirectory(scripts)

