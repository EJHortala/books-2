# Fluid Engine Dev - Jet

burakbayramli/books note - the code is based on

https://github.com/doyubkim/fluid-engine-dev

repo, and specifically the `book-1st-edition` branch of this repo which is 
the code that is closest to the code seen in Kim's book.

[![License](http://img.shields.io/:license-mit-blue.svg)](LICENSE.md) [![Build Status](https://travis-ci.org/doyubkim/fluid-engine-dev.svg?branch=book-1st-edition)](https://travis-ci.org/doyubkim/fluid-engine-dev) [![Build status](https://ci.appveyor.com/api/projects/status/kulihlhy43vbwou6/branch/book-1st-edition?svg=true)](https://ci.appveyor.com/project/doyubkim/fluid-engine-dev/branch/book-1st-edition)

Jet framework is a fluid simulation engine SDK for computer graphics applications that was created by Doyub Kim as part of the book, ["Fluid Engine Development"](https://www.crcpress.com/Fluid-Engine-Development/Kim/p/book/9781498719926). The code is built on C++11 and can be compiled with commonly available compilers such as g++, clang, and Visual Studio. Currently tested platforms are macOS (10.10 or later), Ubuntu (14.04 or later), and Windows (Visual Studio 2015).

The latest code is always available from the [`master`](https://github.com/doyubkim/fluid-engine-dev/tree/master) branch. Since the code is a living thing which evolves over time, the latest from the master could be somewhat different from the code in the book. To find the version that is consistent with the book, checkout the branch [`book-1st-edition`](https://github.com/doyubkim/fluid-engine-dev/tree/book-1st-edition).

### Key Features
* SPH and PCISPH fluid simulators
* Stable fluids-based smoke simulator
* Level set-based liquid simulator
* PIC and FLIP fluid simulators
* Upwind, ENO and FMM level set solvers
* Converters between signed distance function and triangular mesh

Every simulator has both 2-D and 3-D implementations.

## How to Build

To learn how to build, test, and install the SDK, please check out [INSTALL.md](https://github.com/doyubkim/fluid-engine-dev/blob/book-1st-edition/INSTALL.md).

## Documentations

All the documentations for the framework can be found from [the project website](http://doyubkim.github.io/fluid-engine-dev/documentation/) including the API reference.

## Examples

Here are some of the example simulations generated using Jet framework. Corresponding example codes can be found under src/examples. All images are rendered using [Mitsuba renderer](https://www.mitsuba-renderer.org/). Find out more demos from [the project website](http://doyubkim.github.io/fluid-engine-dev/examples/).

![Examples](https://github.com/doyubkim/fluid-engine-dev/raw/book-1st-edition/doc/img/examples.png "Examples")

## License

Jet is under the MIT license. For more information, check out [LICENSE.md](https://github.com/doyubkim/fluid-engine-dev/blob/book-1st-edition/LICENSE.md). Jet also utilizes other open source codes. Checkout [3RD_PARTY.md](https://github.com/doyubkim/fluid-engine-dev/blob/book-1st-edition/3RD_PARTY.md) for more details.
