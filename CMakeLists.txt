cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "ADS1X15.cpp" "ADS1X15.h"
                       INCLUDE_DIRS "."
                       REQUIRES arduino)

project(ADS1X15)
