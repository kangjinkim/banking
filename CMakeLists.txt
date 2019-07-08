cmake_minimum_required( VERSION 3.0 )

project( banking_system )

# include files
include_directories( ./src)

# target
add_executable( banking ./src/banking.cpp)
