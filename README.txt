README
======

This package includes the following files:

|-- Driver.c [This is the driver program which will be used to invoke the MemoryManager]
|-- Makefile [This compiles your Driver.c program to a runnable Driver.out executable]
|-- MemoryManager.c [The MemoryManager is implemented here]
|-- MemoryManager.h [Header file declaring the function exposed from MemoryManager]
|-- README.txt [This file]

To compile:
    gcc *.c
    make

To run:
    ./Driver.out <seed>

For example:
    ./Driver.out 1234

