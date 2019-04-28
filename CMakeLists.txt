project("Temperature Sensor Reader")
cmake_minimum_required(VERSION 3.14)

include_directories(
    ${CMAKE_SOURCE_DIR}/include
    src
)

add_executable(tempsensors  src/temperature_sensor.c
                            src/main.c)