cmake_minimum_required(VERSION 2.8)
project( Snakes-Laders )
include_directories(C:/Users/MuraliR/Downloads/opencv/build/include)
set (OpenCV_DIR C:/Users/MuraliR/Downloads/opencv/build/include)
add_executable( Snakes-Laders src/intotal.c )
target_link_libraries( Snakes-Laders ${OpenCV_LIBS} )
