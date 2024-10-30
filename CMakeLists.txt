cmake_minimum_required(VERSION 3.29)
project(CudaPlaygrounda CUDA)

set(CMAKE_CUDA_STANDARD 17)

add_executable(CudaPlaygrounda main.cu
        main.cu
        main.cu
        main.cu
        main.cu
        main.cu)

set_target_properties(CudaPlaygrounda PROPERTIES
                      CUDA_SEPARABLE_COMPILATION ON)
