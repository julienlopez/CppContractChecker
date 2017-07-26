cmake_minimum_required(VERSION 3.9)

project(LibCppContractChecker)

file(GLOB_RECURSE SOURCE_FILES ./*)
add_library(LibCppContractChecker ${SOURCE_FILES})