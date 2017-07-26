cmake_minimum_required(VERSION 3.9)

project(CppContractChecker)

include_directories(../lib)

file(GLOB_RECURSE SOURCE_FILES ./*)
add_executable(CppContractChecker ${SOURCE_FILES})

target_link_libraries(CppContractChecker LibCppContractChecker)