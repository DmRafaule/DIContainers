cmake_minimum_required(VERSION 3.5)
project(DIContainers VERSION 0.1 DESCRIPTION "General purpose containers module" LANGUAGES CXX)


file( GLOB SOURCES **.cpp )

SetFlags()
SetLibraries( DIDebuger DITime DIMemory DIUtils )
CreateLibrary( ${PROJECT_NAME} )