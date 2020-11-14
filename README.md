# libigl example mex project

Modeled after the [gptoolbox/mex CMake
setup](https://github.com/alecjacobson/gptoolbox/tree/master/mex), this example
project demonstrates a minimal mex function using libigl+eigen (`example.cpp`)
and how to build this function _outside of MATLAB_ using CMake.

## Compilation

    mkdir build
    cd build
    cmake ../
    make
    cd ../

will generate (for example, on mac) `example.mexmaci`
