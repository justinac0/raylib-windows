# Raylib Windows

Compiling and linking raylib can sometimes be a pain to setup
on windows. Now with the release of Raylib 5.5, you can easily
install a mingw c/c++ compiler that includes raylib.

## Setup

1. Install the Raylib provided compiler (for Raylib >= 5.5).
2. Setup environmental path for the devkit bin (default is usually `C:\raylib\w64devkit\bin`).

## Compiling

`Makefile` contains the most basic linking requirements for windows.

Run `make all` to compile `main.c`.