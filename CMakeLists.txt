cmake_minimum_required(VERSION 3.13)

project(RP2040_Neural_Network C CXX ASM)
set(CMAKE_C_STANDARD 11)
set(CMAKE_CXX_STANDARD 17)

set(PICO_SDK_PATH "${CMAKE_CURRENT_LIST_DIR}/pico-sdk")
include(${PICO_SDK_PATH}/external/pico_sdk_import.cmake)

pico_sdk_init()

add_executable(pico_a_nn_training
    pico_a_nn_training.c
)

target_link_libraries(pico_a_nn_training pico_stdlib)
pico_add_extra_outputs(pico_a_nn_training)
