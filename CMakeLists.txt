cmake_minimum_required(VERSION 3.28)
project(RubikCubeSolver)

set(CMAKE_CXX_STANDARD 17)

add_executable(RubikCubeSolver main.cpp
        Models/RubiksCube.cpp
        Models/RubiksCube.h
        Models/RubiksCube3DArray.cpp
        Models/RubiksCube1DArray.cpp
        Models/RubiksCubeBitboard.cpp
        Solver/DFSSolver.h
        Solver/BFSSolver.h
        Solver/IDAstarSolver.h
        Solver/IDDFSSolver.h)
