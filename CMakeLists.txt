cmake_minimum_required(VERSION 3.30)
project(CudaTest VERSION 1.0 LANGUAGES CUDA C CXX)

add_executable(gputest src/vector_add.cu)
add_executable(cputest src/vector_add.c)