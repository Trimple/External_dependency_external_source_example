cmake_minimum_required(VERSION 3.10)

project(External_repo_based_external_dep VERSION 0.1.0)

set(CMAKE_CXX_STANDARD 11) # C++ standard to use
set(CMAKE_CXX_EXTENSIONS OFF) # Do not allow compiler specific features

add_subdirectory(dep_1_cmake)