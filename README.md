A barebones NES emulator written as a school project for Linux. Written in c++11 
and using sdl for video and sound. Cppnes has only been tested on a few no-mmc games, 
mmc1, and mmc3 games. Proven to work:

No-mmc:
* Super Mario Brothers
* Tennis
* Pac-man
* Golf
* Donkey Kong
* Donkey Kong 3

mmc1:
* Tetris
* Megan Man 2
* Lemmings
* Dr. Mario
* Legend of Zelda
* Final Fantasy

mmc3:
* Super Mario Brothers 2
* Super Mario Brothers 3
* Kirby's Adventure
* Final Fantasy 3

Broken for unknown reasons:
* Metroid (probably because of ppu sprite/bg ordering issues)



## Build requirements:
    * SDL 2.0
    * gcc >= 4.6

## To build:
    $ cd cppnes
    $ RELEASE=1 make -j8

## To run:
    cd cppnes
    ./bin/cppnes -r <rom_of_your_choice>

## Controls:
    Start - Enter
    Select - Shift
    A - "n" key
    B - "m" key
    DPAD - arrow keys or FPS standard "wsad" keys

