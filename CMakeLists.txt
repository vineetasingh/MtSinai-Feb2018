cmake_minimum_required(VERSION 2.8)
project(Kristen_Feb2018)
find_package( OpenCV REQUIRED )
add_executable(analyze source.cpp )
target_link_libraries( analyze ${OpenCV_LIBS} )
