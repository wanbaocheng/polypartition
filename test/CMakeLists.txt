include_directories(../src)
add_executable(test test.cpp image.cpp imageio.cpp)
target_link_libraries(test polypartition)