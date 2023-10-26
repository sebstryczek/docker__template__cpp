cmake_minimum_required(VERSION 3.10)

project(HelloWorld)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra")

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_VERBOSE_MAKEFILE on)

add_executable(HelloWorld ../src/main.cpp)

# find_package(Boost REQUIRED)
# target_link_libraries(HelloWorld PRIVATE Boost::boost)
