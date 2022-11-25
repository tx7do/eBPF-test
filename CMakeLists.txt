cmake_minimum_required(VERSION 3.10)

project(ebpf_test)

set(CMAKE_CXX_STANDARD 20)

aux_source_directory(./src DIR_SRCS)

add_executable(${PROJECT_NAME} ${DIR_SRCS})
