cmake_minimum_required(VERSION 3.21.2)

# Название проекта.
set(PROJECT_NAME graphics_template)
project(${PROJECT_NAME} VERSION 0.1.0 LANGUAGES C CXX)

# Название проекта для launch.json.
set(ENV{PROJECT_NAME_ENV} ${PROJECT_NAME})

# Стандарт C++.
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Исходный код.
set(SOURCES 
    src/main.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})

