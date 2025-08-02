cmake_minimum_required(VERSION 3.7.0)
project(VitraeSDK)

SET(CMAKE_BUILD_RPATH_USE_ORIGIN TRUE)

add_subdirectory(Engine)
add_subdirectory(Plugins/OpenGL)
add_subdirectory(Plugins/FormGeneration)
add_subdirectory(Plugins/ShadowFiltering)
add_subdirectory(Plugins/BasicComposition)
add_subdirectory(Plugins/PhongShading)
add_subdirectory(Plugins/Effects)
add_subdirectory(Showcase)