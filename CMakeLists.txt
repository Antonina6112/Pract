cmake_minimum_required (VERSION 3.8)

project (Pract)

add_subdirectory(app1)
add_subdirectory(app2)
add_subdirectory(app3)

add_executable (Pract "Pract.cpp" "Pract.h")

