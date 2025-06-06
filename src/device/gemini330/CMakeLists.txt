# Copyright (c) Orbbec Inc. All Rights Reserved.
# Licensed under the MIT License.

cmake_minimum_required(VERSION 3.5)

target_sources(
    ${OB_TARGET_DEVICE}
    PRIVATE ${CMAKE_CURRENT_LIST_DIR}/G330DeviceInfo.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330DeviceInfo.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330Device.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330Device.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330MetadataTypes.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330MetadataParser.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330AlgParamManager.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330AlgParamManager.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330PresetManager.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330PresetManager.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330DepthWorkModeManager.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330DepthWorkModeManager.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330SensorStreamStrategy.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330SensorStreamStrategy.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330PropertyAccessors.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330PropertyAccessors.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330FrameTimestampCalculator.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330FrameTimestampCalculator.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330FrameInterleaveManager.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330FrameInterleaveManager.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330NetDisparitySensor.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330NetDisparitySensor.hpp
    ${CMAKE_CURRENT_LIST_DIR}/G330NetVideoSensor.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330NetVideoSensor.hpp
	${CMAKE_CURRENT_LIST_DIR}/G330NetAccelSensor.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330NetAccelSensor.hpp
	${CMAKE_CURRENT_LIST_DIR}/G330NetGyroSensor.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330NetGyroSensor.hpp
	${CMAKE_CURRENT_LIST_DIR}/G330NetStreamProfileFilter.cpp
    ${CMAKE_CURRENT_LIST_DIR}/G330NetStreamProfileFilter.hpp
    ${CMAKE_CURRENT_LIST_DIR}/DabaiADevice.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DabaiADevice.hpp
    ${CMAKE_CURRENT_LIST_DIR}/DabaiAMetadataModifier.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DabaiAMetadataModifier.hpp
    ${CMAKE_CURRENT_LIST_DIR}/DaBaiAAlgParamManager.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DaBaiAAlgParamManager.hpp
    ${CMAKE_CURRENT_LIST_DIR}/DaBaiAPresetManager.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DaBaiAPresetManager.hpp

    ${CMAKE_CURRENT_LIST_DIR}/DabaiADevice.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DabaiADevice.hpp
    ${CMAKE_CURRENT_LIST_DIR}/DabaiAMetadataModifier.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DabaiAMetadataModifier.hpp
    ${CMAKE_CURRENT_LIST_DIR}/DaBaiAAlgParamManager.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DaBaiAAlgParamManager.hpp
    ${CMAKE_CURRENT_LIST_DIR}/DaBaiAPresetManager.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DaBaiAPresetManager.hpp

)

