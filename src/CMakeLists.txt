# This is the CMakeLists.txt template for C++17
project(YourProjectName)
# Require minimal cmake version.
cmake_minimum_required(VERSION 3.5)
# Generate a Compilation Database.
set(CMAKE_EXPORT_COMPILE_COMMANDS on)
# Set build type to debug explicitly.
set(CMAKE_BUILD_TYPE Debug)
# Use C++17.
set(CMAKE_CXX_STANDARD 17)
# Customized CXX flags.
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -pedantic")

# Add your executables
add_executable(main main.cpp)
