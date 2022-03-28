cmake_minimum_required(VERSION 3.21)
project(Less32)

set(CMAKE_CXX_STANDARD 14)
add_subdirectory(nlohmann_json)
add_executable(Less32 main.cpp)
target_link_libraries(Less32 PRIVATE nlohmann_json::nlohmann_json)