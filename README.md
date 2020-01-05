[![threading](docs/pictures/header.png)](https://gammasoft71.wixsite.com/xtd-threading)

[![Build Status](https://travis-ci.org/gammasoft71/xtd.threading.svg?branch=master)](https://travis-ci.org/gammasoft71/xtd.threading)
[![Build status](https://ci.appveyor.com/api/projects/status/6483r6dkpixsyxs9?svg=true)](https://ci.appveyor.com/project/gammasoft71/xtd-threading)
[![codecov](https://codecov.io/gh/gammasoft71/xtd.threading/branch/master/graph/badge.svg)](https://codecov.io/gh/gammasoft71/xtd.threading)
[![Documentation](https://codedocs.xyz/gammasoft71/xtd.threading.svg)](https://codedocs.xyz/gammasoft71/xtd.threading/)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg?label=xtd-threading%20website)](https://gammasoft71.wixsite.com/xtd-threading)
[![license](https://img.shields.io/github/license/gammasoft71/xtd.threading.svg)](LICENSE.md)
[![SourceForge Download threading](https://img.shields.io/sourceforge/dt/threading.svg)](https://sourceforge.net/projects/threading/files/latest/download)
[![GitHub top language](https://img.shields.io/github/languages/top/gammasoft71/xtd.threading.svg)](README.md)
[![Windows](https://img.shields.io/badge/os-Windows-004080.svg)](README.md)
[![macOS](https://img.shields.io/badge/os-macOS-004080.svg)](README.md)
[![Linux](https://img.shields.io/badge/os-Linux-004080.svg)](README.md)

# Features

For more information see [Documentation](docs).

# Examples

timer.cpp:

```c++
#include <xtd/xtd.threading>
#include <iostream>
#include <string>

using namespace std;
using namespace xtd;

// The main entry point for the application.
int main() {
}
```

CMakeLists.txt:

```cmake
cmake_minimum_required(VERSION 3.3)

project(timer)
find_package(xtd.threading REQUIRED)
add_executable(${PROJECT_NAME} timer.cpp)
target_link_libraries(${PROJECT_NAME} xtd.threading)
```

For more examples see [examples](examples)

# Download and install

Before running examples you must download and install threading. To download and install it read Downloads file.

