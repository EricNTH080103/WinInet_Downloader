cmake_minimum_required(VERSION 3.16)
project(WinInet)

set(CMAKE_CXX_STANDARD 17)

link_libraries(D:/MinGW/lib/libwininet.a)

add_executable(WinInet main.cpp)