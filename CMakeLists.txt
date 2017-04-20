cmake_minimum_required(VERSION 3.6)
project(grbl_1_1f_20170131)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    grbl/examples/grblUpload/grblUpload.ino
    grbl/examples/grblUpload/license.txt
    grbl/examples/grblWrite_BuildInfo/grblWrite_BuildInfo.ino
    grbl/examples/grblWrite_BuildInfo/license.txt
    grbl/config.h
    grbl/coolant_control.c
    grbl/coolant_control.h
    grbl/cpu_map.h
    grbl/defaults.h
    grbl/eeprom.c
    grbl/eeprom.h
    grbl/gcode.c
    grbl/gcode.h
    grbl/grbl.h
    grbl/jog.c
    grbl/jog.h
    grbl/limits.c
    grbl/limits.h
    grbl/main.c
    grbl/motion_control.c
    grbl/motion_control.h
    grbl/nuts_bolts.c
    grbl/nuts_bolts.h
    grbl/planner.c
    grbl/planner.h
    grbl/print.c
    grbl/print.h
    grbl/probe.c
    grbl/probe.h
    grbl/protocol.c
    grbl/protocol.h
    grbl/report.c
    grbl/report.h
    grbl/serial.c
    grbl/serial.h
    grbl/settings.c
    grbl/settings.h
    grbl/spindle_control.c
    grbl/spindle_control.h
    grbl/stepper.c
    grbl/stepper.h
    grbl/system.c
    grbl/system.h
    COPYING
    Makefile)

add_executable(grbl_1_1f_20170131 ${SOURCE_FILES})