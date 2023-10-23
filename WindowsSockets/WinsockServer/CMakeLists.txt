# cmake最低要求
cmake_minimum_required( VERSION 3.1.0 )
project(WinsockServer)
aux_source_directory(. DIR_SRCS)

add_executable(${PROJECT_NAME} ${DIR_SRCS})
SET_EXAMPLE_PROPERTIES(${PROJECT_NAME})