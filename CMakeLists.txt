cmake_minimum_required(VERSION 3.21)
project(ObserverProject)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(ObserverProject
        ConcreteObserver.h
        ConcreteObserverImpl.cpp
        ConcreteSubject.h
        main.cpp
        ObserverInterface.h
        Subject.h
        SubjectImpl.cpp)
