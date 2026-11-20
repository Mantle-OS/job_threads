cmake_minimum_required(VERSION 3.16)
project(JobThreads
    VERSION 0.0.1
    LANGUAGES CXX
)

add_subdirectory(libs)
enable_testing()
add_subdirectory(tests)
add_subdirectory(docs)
