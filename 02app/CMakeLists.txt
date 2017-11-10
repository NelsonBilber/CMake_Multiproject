cmake_minimum_required(VERSION 2.6)
project (02app)

set (PROJECT_SOURCE_DIR ${CMAKE_CURRENT_SOURCE_DIR})

set(PROJECT2_SRCS
${PROJECT_SOURCE_DIR}/main.cpp
)

add_executable(${PROJECT_NAME} ${PROJECT2_SRCS})
