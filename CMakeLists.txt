cmake_minimum_required(VERSION 3.19)
project(C_Programming_Language C)

set(CMAKE_C_STANDARD 11)

#Chapter 1 files
add_executable(C1_Hello_world Chapter1/Hello_world.c)
add_executable(C1_Fahrenheit_Celsius_Table Chapter1/Fahrenheit_Celsius_Table.c)
