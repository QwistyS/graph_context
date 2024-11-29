cmake_minimum_required(VERSION 3.10)
project(graph_ctx)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SOURCE
)

# Do i need to add qwistys lib here? probably yes.
# TODO: create git repo and link stuff here.
# add_library(qwistys_lib STATIC ${QWISTYS_SOURCES})

# target_include_directories(qwistys_lib
#     PUBLIC
#         $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/inc>
#         $<INSTALL_INTERFACE:include>
# )

# # Optionally enable telemetry
# option(ENABLE_QWISTYS_TELEMETRY "Enable telemetry for qwistys_lib" OFF)
# if(ENABLE_QWISTYS_TELEMETRY)
#     target_compile_definitions(qwistys_lib PUBLIC ENABLE_QWISTYS_TELEMETRY)
# endif()
