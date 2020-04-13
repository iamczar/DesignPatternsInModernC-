cmake_minimum_required(VERSION 3.12.1)

project(main)

 set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(main
    "src/main.cpp"
)


add_executable(${PROJECT_NAME} ${main})