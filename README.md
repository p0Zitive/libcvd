# libCVD
By p0zzy: Mac os Sierra compilation support.

Note, the master branch is now libCVD-2.0 which is in beta and requires C++14.

## Compiling and installing

To install on a unix system:

./configure && make && sudo make install

### Important update!
To configure on a mac system:
./configure_osx

To verify that a few things work, you can optioinally run

make test


## System compatibility

You need a C++14 compiler. 

All libraries are optional but you will be missing features if the libraries
aren't present. The configure script will tell you what's present and what's
not.


## Documentation

[![Documentation Status](https://codedocs.xyz/edrosten/libcvd.svg)](https://codedocs.xyz/edrosten/libcvd/)

Latest documentation here: https://codedocs.xyz/edrosten/libcvd/ or just run Doxygen.


## Status of unit tests
[![Build Status](https://drone.io/github.com/edrosten/libcvd/status.png)](https://drone.io/github.com/edrosten/libcvd/latest)

