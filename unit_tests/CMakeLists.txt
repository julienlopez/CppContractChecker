cmake_minimum_required(VERSION 3.9)

project(unit_tests)

include_directories(../lib)
include_directories(../third_party)

file(GLOB_RECURSE SOURCE_FILES ./*)
add_executable(unit_tests ${SOURCE_FILES})

target_link_libraries(unit_tests LibCppContractChecker)
