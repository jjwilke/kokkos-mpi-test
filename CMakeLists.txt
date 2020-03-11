cmake_minimum_required (VERSION 3.10)
cmake_policy(SET CMP0074 NEW)

project (KokkosTutorial04 CXX)

find_package(Kokkos REQUIRED)

add_executable(04_Exercise exercise_4_solution.cpp)
target_link_libraries(04_Exercise Kokkos::kokkos)
