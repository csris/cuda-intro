cmake_minimum_required(VERSION 3.22)

project(
    CUDAIntro
    VERSION 0.1
    DESCRIPTION "An Even Easier Introduction to CUDA"
    LANGUAGES CXX CUDA)

include(CheckLanguage)
check_language(CUDA)

add_subdirectory(cmd)
