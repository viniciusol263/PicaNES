cmake_minimum_required(VERSION 3.0.0)
project(PicaNES VERSION 1.0.0)

set(CMAKE_CXX_STANDARD 20)

set(PICANES_ROOT_DIR ${CMAKE_SOURCE_DIR})

set(PICANES_MAIN main.cpp)
set(PICANES_SRC ${PICANES_ROOT_DIR}/PicaNESMain/PicaNESMain.cpp)

add_executable(PicaNES ${PICANES_MAIN} ${PICANES_SRC})
