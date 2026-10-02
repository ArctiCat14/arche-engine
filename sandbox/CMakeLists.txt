add_executable(arche-sandbox
    source/main.cpp
)

target_link_libraries(arche-sandbox
    PRIVATE
    arche-engine
)

target_compile_options(arche-sandbox PRIVATE -Wall -Wextra)
