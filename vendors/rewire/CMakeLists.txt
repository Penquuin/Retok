set(sources main.c)
set(include ${CMAKE_CURRENT_SOURCE_DIR}/include)
set(headers ${include}/rewire.h)

add_library(rewire ${sources} ${headers})
target_include_directories(rewire PUBLIC ${include})