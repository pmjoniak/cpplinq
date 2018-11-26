project(cpp-linq)
cmake_minimum_required(VERSION 2.8)

include_directories (CppLinq)

install (DIRECTORY CppLinq/ DESTINATION include FILES_MATCHING PATTERN "*.hpp")