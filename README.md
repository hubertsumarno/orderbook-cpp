# Orderbook

This project aims to implement an orderbook in C++20.

This project is done for educational purposes only.

## Order Types

The following order types are supported:

* GoodTillCAncel
* FillAndKill
* FillOrKill
* GoodForDay

## Code stucture

All code with regards to the orderbook is part of a library called `orderbook_lib`.

This library is used by the main application source code found in `app/main.cpp`.

## Build requirements

The following dependencies are required to build the application:

* C++ compiler that supports C++20 (e.g. g++, clang++)
* CMake

