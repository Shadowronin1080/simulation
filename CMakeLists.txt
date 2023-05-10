cmake_minimum_required(VERSION 3.25)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)


set(HEADERS src/main.h)

project(game)




add_executable(${PROJECT_NAME} src/main.cpp ${HEADERS} )

