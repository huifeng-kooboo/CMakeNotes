#CMakeLists.txt 编写
cmake_minimum_required(VERSION 2.8)  #设置CMake最低支持版本
project(HelloWorld)   # 设置项目名称
add_executable(demo HelloWorld.cpp)  # 第一个参数为需要生成的exe文件名 或者在linux下也是类似，第二个参数为源文件