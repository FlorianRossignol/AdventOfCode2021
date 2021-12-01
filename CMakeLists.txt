cmake_minimum_required(VERSION 3.14)

if(WIN32)
	add_compile_options("/std:c++latest")
endif(WIN32)

set(CMAKE_CXX_STANDARD 17)

project(AdventOfCode2021)


add_executable(AdventOfCode2021

	${PROJECT_SOURCE_DIR}/main/main.cpp
)
