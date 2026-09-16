cmake_minimum_required(VERSION 3.15)

project(ThePankeyEngine_Utility_Log_Windows)

if(NOT TARGET ThePankeyEngine_Utility_Log_Windows)

    add_library(ThePankeyEngine_Utility_Log_Windows INTERFACE)

    target_include_directories(
        ThePankeyEngine_Utility_Log_Windows
          INTERFACE
            ${CMAKE_CURRENT_SOURCE_DIR}
    )

endif()