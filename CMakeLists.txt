
cmake_minimum_required(VERSION 2.8)

project( examples )

find_package( OpenCV REQUIRED )

include_directories( ${OpenCV_INCLUDE_DIRS} )

add_executable( example_02-01 example_02-01.cpp )
add_executable( example_02-02 example_02-02.cpp )
add_executable( example_02-03 example_02-03.cpp )
add_executable( example_02-04 example_02-04.cpp )
add_executable( example_02-05 example_02-05.cpp )
add_executable( example_02-06 example_02-06.cpp )
add_executable( example_02-07 example_02-07.cpp )
add_executable( example_02-08 example_02-08.cpp )
add_executable( example_02-09 example_02-09.cpp )
add_executable( example_02-10 example_02-10.cpp )
add_executable( example_02-11 example_02-11.cpp )
add_executable( example_04-01 example_04-01.cpp )
add_executable( example_04-02 example_04-02.cpp )
add_executable( example_04-03 example_04-03.cpp )
add_executable( example_04-04 example_04-04.cpp )
add_executable( example_05-01 example_05-01.cpp )
add_executable( example_07-01 example_07-01.cpp )
add_executable( example_08-01 example_08-01.cpp )
add_executable( example_08-02 example_08-02.cpp )
add_executable( example_08-03 example_08-03.cpp )
add_executable( example_09-01 example_09-01.cpp )
add_executable( example_09-02 example_09-02.cpp )
add_executable( example_09-03 example_09-03.cpp )
#...
add_executable( example_16-01 example_16-01.cpp )

target_link_libraries( example_02-01 ${OpenCV_LIBS} )
target_link_libraries( example_02-02 ${OpenCV_LIBS} )
target_link_libraries( example_02-03 ${OpenCV_LIBS} )
target_link_libraries( example_02-04 ${OpenCV_LIBS} )
target_link_libraries( example_02-05 ${OpenCV_LIBS} )
target_link_libraries( example_02-06 ${OpenCV_LIBS} )
target_link_libraries( example_02-07 ${OpenCV_LIBS} )
target_link_libraries( example_02-08 ${OpenCV_LIBS} )
target_link_libraries( example_02-09 ${OpenCV_LIBS} )
target_link_libraries( example_02-10 ${OpenCV_LIBS} )
target_link_libraries( example_02-11 ${OpenCV_LIBS} )
target_link_libraries( example_04-01 ${OpenCV_LIBS} )
target_link_libraries( example_04-02 ${OpenCV_LIBS} )
target_link_libraries( example_04-03 ${OpenCV_LIBS} )
target_link_libraries( example_04-04 ${OpenCV_LIBS} )
target_link_libraries( example_05-01 ${OpenCV_LIBS} )
target_link_libraries( example_07-01 ${OpenCV_LIBS} )
target_link_libraries( example_08-01 ${OpenCV_LIBS} )
target_link_libraries( example_08-02 ${OpenCV_LIBS} )
target_link_libraries( example_08-03 ${OpenCV_LIBS} )
target_link_libraries( example_09-01 ${OpenCV_LIBS} )
target_link_libraries( example_09-02 ${OpenCV_LIBS} )
target_link_libraries( example_09-03 ${OpenCV_LIBS} )
# ...
target_link_libraries( example_16-01 ${OpenCV_LIBS} )




