cmake_minimum_required(VERSION 3.3)

# Solution
project(src)

# Projects
add_subdirectory(xtd_threading)
if (IS_MAIN_PROJECT)
  add_subdirectory(xtd_tunit)
endif ()
