cmake_minimum_required(VERSION 3.22)

project(chat)

set(CMAKE_CXX_STANDARD 20)

set(CMAKE_C_COMPILER gcc)
set(CMAKE_CXX_compiler g++)

find_package(Boost 1.74.0 COMPONENTS filesystem)
find_package(SQLite3 REQUIRED)



add_subdirectory(src)