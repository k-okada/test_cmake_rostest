cmake_minimum_required(VERSION 2.8.3)
project(test4)

find_package(catkin REQUIRED rostest)

add_rostest(test.test)
