cmake_minimum_required(VERSION 3.30)
project(ScorchEngine)

include_directories(${CMAKE_SOURCE_DIR}/include)
link_directories(${CMAKE_SOURCE_DIR}/lib)

add_executable(ScorchEngine src/main.cpp)
target_link_libraries(ScorchEngine glfw3)
target_link_libraries(ScorchEngine vulkan-1)