# Tetris-ever

[![CMake](https://github.com/Joker2770/Tetris-ever/actions/workflows/cmake.yml/badge.svg)](https://github.com/Joker2770/Tetris-ever/actions/workflows/cmake.yml)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/8f73ac975e644fd0b3dff50a72f589c2)](https://app.codacy.com/gh/Joker2770/Tetris-ever?utm_source=github.com&utm_medium=referral&utm_content=Joker2770/Tetris-ever&utm_campaign=Badge_Grade_Settings)
[![tetris-ever](https://snapcraft.io/tetris-ever/badge.svg)](https://snapcraft.io/tetris-ever)

A simple tetris game is written with C, and is rendered by SDL2.

## Dependencies
Required:
* [cmake](http://www.cmake.org) - buildsystem
* g++ (>= 7.4.0 recommended)
* gcc (>= 7.4.0 recommended)
* libsdl2-dev,libsdl2-ttf-dev (Linux), sdl2.nuget,sdl2_ttf.nuget (Windows)

## Build on Ubuntu(Linux)
~~~
sudo apt install libsdl2-dev libsdl2-ttf-dev
git clone https://github.com/Joker2770/Tetris-ever.git
cd Tetris-ever
mkdir build
cd build
cmake ..
make
cp ../res/bb3273.ttf ./
./Tetris-ever
sudo make install
Tetris-ever
~~~

## Build on Windows
~~~
git clone https://github.com/Joker2770/Tetris-ever.git
cd Tetris-ever/msvc/
~~~
Then double click 'Tetris-ever.sln', build with Visual Studio, do not forget copy 'bb3273.ttf' to program directory.
