cmake_minimum_required(VERSION 3.0.0)
project(WinAPI32)

include(CTest)
enable_testing()

add_executable(WinAPI32 main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
