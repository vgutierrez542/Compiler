cmake_minimum_required(VERSION 3.13)
project(CCompiler)

set(CMAKE_CXX_STANDARD 14)
include_directories(.)

add_executable(CCompiler
        ccompiler.hpp
        ccompiler.cpp
        cscanner.cpp
        cscanner.hpp
        definitions.h
        symboltable.cpp
        symboltable.hpp
        token.cpp
        token.h
        statetables.cpp
        statetables.h
        ir.cpp
        ir.h
        cparser.cpp
        cparser.hpp
        parsetree.cpp
        parsetree.hpp
        instructions.cpp
        instructions.h
        assembly.cpp
        assembly.h
        assemblycontext.cpp
        assemblycontext.h)
