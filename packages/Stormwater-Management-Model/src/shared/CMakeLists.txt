#
# CMakeLists.txt - CMake configuration file for swmm/src/shared
#
# Created: Aug 26, 2020
# Updated: Jan 12, 2025
#
# Author: Michael E. Tryby
#


set(
  SHARED_SOURCES
    cstr_helper.c
    datetime.c
)

set(
  SHARED_HEADERS
    cstr_helper.h
    datetime.h
)

add_library(
  shared_objs 
    OBJECT 
        ${SHARED_SOURCES}
)
