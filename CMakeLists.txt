cmake_minimum_required(3.20)
project(test)
set(CMAKE_C_STANDARD 99)

include_directories(${PROJECT_SOURCE_DIR}/include)
aux_source_directory(${PROJECT_SOURCE_DIR}/src SRC_LIST)
aux_source_directory(${PROJECT_SOURCE_DIR}/src SRC_LIST)

