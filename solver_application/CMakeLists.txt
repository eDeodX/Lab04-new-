cmake_minimum_required(VERSION 3.10)
project(solver_app)

add_executable(solver_app ${CMAKE_CURRENT_SOURCE_DIR}/solver.cpp)
target_link_libraries(solver_app PUBLIC formatter_ex solver)