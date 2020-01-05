cmake_minimum_required(VERSION 3.3)

project(timer)
find_package(xtd.delegates REQUIRED)
add_executable(${PROJECT_NAME} timer.cpp)
target_link_libraries(${PROJECT_NAME} xtd.threading)
set_target_properties(${PROJECT_NAME} PROPERTIES FOLDER "xtd.threading")
