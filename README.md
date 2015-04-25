# CHIP-8
A [CHIP-8](http://en.wikipedia.org/wiki/CHIP-8) emulator written in the [Rust](http://www.rust-lang.org/) programming language. A few sample game screenshots below.

## Overview
This repository contains the source code for a chip8 emulator written in Rust. You will want to compile against the latest version of Rust. See the secion in the official Rust Book for [installing](http://doc.rust-lang.org/nightly/book/installing-rust.html) the Rust binaries, including the Rust package manager Cargo. 

Brix
--- 
![brix.png](http://wm9.github.io/chip8/images/brix.png "Brix")

Space Invaders
---
![space_invaders.png](http://wm9.github.io/chip8/images/space_invaders.png "Space Invaders")

Pong
---
![pong.png](http://wm9.github.io/chip8/images/pong.png "Pong")

Tetris
---
![tetris.png](http://wm9.github.io/chip8/images/tetris.png "Tetris")

## Requirements
The windowing system was built with SDL2. Windows and Mac OSX binaries are available for [download](https://www.libsdl.org/download-2.0.php) from the SDL website. 

**Ubuntu**:  
sudo apt-get install libsdl2-dev

**MacPorts**:  
sudo port install libsdl2  
export LIBRARY\_PATH="${LIBRARY\_PATH}:/opt/local/lib"

**HomeBrew**:  
brew install sdl2  
export LIBRARY\_PATH="${LIBRARY\_PATH}:/usr/local/lib"

## Compile and run
E.g., from inside the chip8 source folder: **cargo run roms/brix.ch8**

## Keys
The CHIP-8 specification has a 16 key hexadecimal keypad with the following layout:

| 1 | 2  | 3 | c |
| --- |---| ---| --- |
| 4 | 5  | 6 | d |
| 7 | 8  | 9 | e |
| a | 0  | b | f |

## References
[Cowgod's Chip-8 Technical Reference](http://devernay.free.fr/hacks/chip8/C8TECH10.HTM)   
[MASTERING CHIP-8 by Matthew Mikolay](http://mattmik.com/chip8.html)

## Travis CI automated build status
[![Build Status](https://travis-ci.org/wm9/chip8.svg)](https://travis-ci.org/wm9/chip8)



