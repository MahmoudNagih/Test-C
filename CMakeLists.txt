cmake_minimum_required(VERSION 3.1)
PROJECT(hello)
# with CACHE:CMake allows external override.
set(APP_NAME hello_app CACHE STRING "Application name")
add_executable(${APP_NAME} hello-git.cpp)

install(TARGETS ${APP_NAME} DESTINATION bin)
