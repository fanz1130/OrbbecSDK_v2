# Copyright (c) Orbbec Inc. All Rights Reserved.
# Licensed under the MIT License.

cmake_minimum_required(VERSION 3.5)

target_sources(
    ${OB_TARGET_DEVICE}
    PRIVATE  ${CMAKE_CURRENT_LIST_DIR}/FemtoMegaDevice.hpp
             ${CMAKE_CURRENT_LIST_DIR}/FemtoMegaDevice.cpp
             ${CMAKE_CURRENT_LIST_DIR}/FemtoMegaIDevice.hpp
             ${CMAKE_CURRENT_LIST_DIR}/FemtoMegaIDevice.cpp
             ${CMAKE_CURRENT_LIST_DIR}/FemtoMegaDeviceInfo.hpp
             ${CMAKE_CURRENT_LIST_DIR}/FemtoMegaDeviceInfo.cpp
             ${CMAKE_CURRENT_LIST_DIR}/FemtoMegaPropertyAccessor.hpp
             ${CMAKE_CURRENT_LIST_DIR}/FemtoMegaPropertyAccessor.cpp
             ${CMAKE_CURRENT_LIST_DIR}/FemtoMegaFrameTimestampCalculator.hpp
             ${CMAKE_CURRENT_LIST_DIR}/FemtoMegaFrameTimestampCalculator.cpp
        )

