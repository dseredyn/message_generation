cmake_minimum_required(VERSION 2.8.3)
project(message_generation_subsystem_buffers)

find_package(catkin REQUIRED)

catkin_package(CATKIN_DEPENDS gencpp_subsystem_buffers geneus gennodejs genlisp genmsg genpy)
