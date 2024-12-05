cmake_minimum_required(VERSION 3.10)

project(My3DViewer)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(My3DViewer
    src/main.cpp
    src/glad.c
    src/GeometryPrimitives.cpp
    src/OpenglRenderSystem.cpp
    src/ViewerWindow.cpp
)

find_package(glm CONFIG REQUIRED)
find_package(glfw3 CONFIG REQUIRED)
find_package(glad CONFIG REQUIRED)

target_link_libraries(My3DViewer PRIVATE glm::glm glfw glad::glad)
