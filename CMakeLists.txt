cmake_minimum_required(VERSION 3.20)
project(js)

set(CMAKE_CXX_STANDARD 20)

add_executable(js main.cpp ast.cpp ast.h interpreter.cpp interpreter.h lexer.cpp lexer.h parser.cpp parser.h object.cpp object.h)

add_subdirectory(tests)