cmake_minimum_required(VERSION 3.1)
PROJECT(hello_cmake)
add_executable(${PROJECT_NAME} hello-git.cpp)

install(TARGETS ${PROJECT_NAME} DESTINATION bin)
