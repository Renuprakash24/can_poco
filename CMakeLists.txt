cmake_minimum_required(VERSION 3.16.3)

project(hello_world)


add_executable(app can_poco/include/Can_main.cpp)

target_compile_features(app PUBLIC cxx_std_11)

target_include_directories(app PUBLIC ${/root/.jenkins/workspace/now/include} /include)

target_include_directories(app PUBLIC ${/root/.jenkins/workspace/now/Poco /include}

