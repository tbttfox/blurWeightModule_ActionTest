cmake_minimum_required(VERSION 3.2.2)
project(blurWeightModule)
SET(MODULE_NAME ${PROJECT_NAME} CACHE STRING "Name of the module")
SET(MAYA_VERSION 2020 CACHE STRING "Maya version number")

# Compiled submodules
add_subdirectory(submodules/blurSkin)
add_subdirectory(submodules/brSkinBrush)
add_subdirectory(submodules/wireframeDisplay)

