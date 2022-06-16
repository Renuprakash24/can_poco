cmake_minimum_required(VERSION 3.16.3)

project(hello_world)
target_compile_features(app PUBLIC cxx_std_11)
add_executable(app can_poco/include/Can_main.cpp)
target_include_directories(app PUBLIC can_poco Poco)












