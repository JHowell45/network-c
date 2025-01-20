cmake_minimum_required(VERSION 3.30)
project(network-c)

###############################################
# Variables
###############################################
set(SRC ${CMAKE_CURRENT_SOURCE_DIR}/src)

###############################################
# Executables
###############################################
add_executable(server ${SRC}/server.c)