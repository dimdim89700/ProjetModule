CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

PROJECT(hello)

ADD_EXECUTABLE(hello hello.c main.c)
ADD_EXECUTABLE(test_hello test.c hello.c)
