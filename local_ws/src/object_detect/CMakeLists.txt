cmake_minimum_required(VERSION 2.8)
project( object_detect )
find_package( OpenCV REQUIRED )
add_executable( object_detect src/object_detect.cpp )
target_link_libraries( object_detect ${OpenCV_LIBS} )

