#http://www.cmake.org/cmake/help/cmake2.6docs.html
cmake_minimum_required (VERSION 2.6)
project (Model_fitting)


FIND_PACKAGE( OpenCV REQUIRED )


ADD_EXECUTABLE(Model_fitting src/main.cpp)
TARGET_LINK_LIBRARIES(Model_fitting ${OpenCV_LIBS})
