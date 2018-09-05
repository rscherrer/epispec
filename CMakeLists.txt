cmake_minimum_required(VERSION 3.10)
project(epispec)

set(CMAKE_CXX_STANDARD 11)
set(SOURCE_FILES ../epispec/main.cpp ../epispec/random.cpp ../epispec/individual.cpp ../epispec/architecture.cpp ../epispec/analysis.cpp)

# blabla

add_executable(epispec ../epispec/main.cpp ../epispec/random.cpp ../epispec/random.h ../epispec/individual.cpp ../epispec/individual.h ../epispec/analysis.cpp ../epispec/analysis.h ../epispec/architecture.cpp)