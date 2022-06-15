cmake_minimum_required(VERSION 3.16.3)

project(hello_world)


add_executable(app Can_main.cpp)

target_compile_features(app PUBLIC cxx_std_11)

target_include_directories(app PUBLIC ${} /include)
