cmake_minimum_required(VERSION 3.8)

project(learningCC LANGUAGES CXX)

FILE(GLOB SC_FILES "./include/.*h", "./src/.*cpp", "./include/.*hpp", "./src/.*cc")

add_executable(${PROJECT_NAME} ${SC_FILES}) 
