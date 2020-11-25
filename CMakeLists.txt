cmake_minimum_required(VERSION 3.8)
project(test-ci VERSION 1.0.0 LANGUAGES C)

add_subdirectory(src)

enable_testing()
add_test(NAME hello_world COMMAND echo "Testsuite: Hello World !")
