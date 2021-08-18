# ./app/CMakeLists.txt -- More Modern CMake

# Requires CMake 3.12, but also works with 3.13 policies set.
cmake_minimum_required( VERSION 3.12...3.13 )
project( CalculatorApp
         VERSION 1.0
         DESCRIPTION "My fancy calculator app." )

add_executable( EvalCI )
target_sources( EvalCI PRIVATE "src/main.cpp" )
