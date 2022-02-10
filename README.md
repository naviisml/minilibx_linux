This is the MinilibX, a simple X-Window (X11R6) programming API
in C, designed for students, suitable for X-beginners.


Contents

 - source code in C to create the mlx library
 - man pages (in man/ directory)
 - a test program (in test/ directory) is built
   with the library
 - a public include file mlx.h
 - a tiny configure script to generate an appropriate Makefile.gen

Requirements for Linux

 - MinilibX only support TrueColor visual type (8,15,16,24 or 32 bits depth)
 - gcc
 - make
 - X11 include files (package xorg)
 - XShm extension must be present (package libxext-dev)
 - Utility functions from BSD systems - development files (package libbsd-dev)
 - **e.g. _sudo apt-get install gcc make xorg libxext-dev libbsd-dev_ (Debian/Ubuntu)**
