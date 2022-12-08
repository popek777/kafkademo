cmake_minimum_required(VERSION 3.15)
project(kafkademo CXX)

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

add_executable(kafkademo
  kafkademo.cpp)
target_link_libraries(kafkademo ${CONAN_LIBS})

add_executable(kafkafulldemo
  kafkafulldemo.cpp)
target_link_libraries(kafkafulldemo ${CONAN_LIBS})
