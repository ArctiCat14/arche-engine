add_library(arche-engine STATIC
    source/engine.cpp
)

target_include_directories(arche-engine
    PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}/include
)

target_compile_options(arche-engine PRIVATE -Wall -Wextra)
