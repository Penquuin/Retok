cmake_minimum_required (VERSION 3.10)
project (Retok)

set(SRC ${CMAKE_SOURCE_DIR}/src)
set(VENDOR ${CMAKE_SOURCE_DIR}/vendors)

add_subdirectory(${VENDOR}/rewire)
add_subdirectory(${SRC})