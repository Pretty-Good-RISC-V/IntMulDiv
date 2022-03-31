add_library(IntMulDiv INTERFACE)
add_library(IntMulDiv::IntMulDiv ALIAS IntMulDiv)

target_include_directories(IntMulDiv INTERFACE "${CMAKE_CURRENT_SOURCE_DIR}")
