# LC-3 Virtual Machine

A clean, efficient C++ implementation of the **LC-3** (Little Computer 3) virtual machine.

## About

This project implements the LC-3 architecture — a simple, pedagogical computer architecture widely used in university courses (notably *Introduction to Computer Systems* by Patt & Patel).

It can load and run compiled LC-3 assembly programs (`.obj` files).

## Features

- Full LC-3 instruction set support
- Trap routines (GETC, OUT, PUTS, IN, PUTSP, HALT)
- Memory-mapped keyboard I/O
- Proper condition flags (N, Z, P)
- Signal handling (Ctrl+C support)
- Cross-platform Unix/Linux/macOS ready (uses termios)
- Built with CMake
