
# Example of CMakeLists.txt
```
cmake_minimum_required (VERSION 2.6)
project (Tutorial)

add_subdirectory (sub_dir)

include_directories(inc_dir)
link_directories(link_dir)

add_executable(exec_name *.cpp)
add_library(lib_name *.cpp)

target_link_libraries(target_name libraries)
target_compile_definitions(target_name <INTERFACE|PUBLIC|PRIVATE> options)
```
# Variables
```
PROJECT_SOURCE_DIR
```

# Debug
```
cmake -DCMAKE_BUILD_TYPE=Debug
```

# References
1. [CMake](http://www.aosabook.org/en/cmake.html)
2. [cmake tutorial](https://cmake.org/cmake-tutorial/)
3. [FindFLEX](https://cmake.org/cmake/help/v3.0/module/FindFLEX.html)
4. [cmake-variables](https://cmake.org/cmake/help/latest/manual/cmake-variables.7.html)
5. [Modern CMake with target_link_libraries](https://schneide.blog/2016/04/08/modern-cmake-with-target_link_libraries/)
