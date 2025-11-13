add_subdirectory(src)

file(GLOB SOURCES "src/*.cpp")

include_directories(src)

add_executable(Chapter01 ${SOURCES})