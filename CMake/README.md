# CMake

* [CMake Tutoral](https://cmake.org/cmake-tutorial/)

## Getting started

### Basic routine

```sh
mkdir build
cd build
cmake ..
```

Then it will generate a Makefile

```sh
make
```

Then it will generate executable binary

### Simplest Version

* tutorial.cxx - compute the square root of a number

Test the program

```sh
$ ./Tutorial 9
The square root of 9 is 3
```

### Simplest Version with Version Number and Configured Header File

> provide our executable and project with a version number

* TutorialConfig.h.in
* tutorial.cxx - compute the square root of a number
  * modify tutorial.cxx to include the configured header file and to make use of the version numbers

```sh
$ ./Tutorial
./Tutorial Version 1.0
Usage: ./Tutorial number

$ ./Tutorial 3
The square root of 3 is 1.73205
```

### Adding a Library

* MathFunctions/
  * CMakeLists.txt
  * mysqrt.cxx
* tutorial.cxx
* TutorialConfig.h.in

TO BE DONE

## Links

* [VSCode CMake Tools - Getting Started](https://vector-of-bool.github.io/docs/vscode-cmake-tools/getting_started.html)

* [Using OpenCV with gcc and CMake](https://docs.opencv.org/3.4/db/df5/tutorial_linux_gcc_cmake.html)
