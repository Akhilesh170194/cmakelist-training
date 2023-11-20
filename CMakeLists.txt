cmake_minimum_required(VERSION 3.10.2)

project(hello)
add_executable(${PROJECT_NAME} hello.cc)
install(TARGETS hello DESTINATION bin)