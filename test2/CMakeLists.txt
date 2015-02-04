cmake_minimum_required(VERSION 2.8.3)
project(test2)

find_package(catkin REQUIRED rostest)

add_rostest(test.test)
