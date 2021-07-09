<a href="super-tiny-compiler.py"><img width="731" alt="THE SUPER TINY COMPILER" src="https://cloud.githubusercontent.com/assets/952783/14413766/134c4068-ff39-11e5-996e-9452973299c2.png"/></a>

***Welcome to The Super Tiny Compiler!***

This is a Python version of [The Super Tiny Compiler](https://github.com/thejameskyle/the-super-tiny-compiler) originally developed in JavaScript by [@thejameskyle](https://github.com/thejameskyle)


## Overview

[JamieBuilds](https://github.com/jamiebuilds/the-super-tiny-compiler) developed a wonderfully educative compiler example a few years ago in Javascript, and this is a 250 line python implementation. It's the code for [this](https://youtu.be/jeOU6KJFi8c) live Battle Royale game show hosted by Siraj Raval on Youtube. It takes an input expression in LISP and converts it into C.

### If we had two functions `add` and `subtract` they would be written like this:
###
###                  LISP                      C
###
###   2 + 2          (add 2 2)                 add(2, 2)
###   4 - 2          (subtract 4 2)            subtract(4, 2)
###   2 + (4 - 2)    (add 2 (subtract 4 2))    add(2, subtract(4, 2))


## Dependencies

- copy
- re

## Usage

Type 'python compiler.py' into a command line to run this code. You can switch out the input expression in the main function with your own to test out different outputs.

## Related Implementations

- [Hazbo](https://github.com/hazbo/the-super-tiny-compiler)
- [ill-look-later](https://github.com/ill-look-later/mini-wasm) 
- [josegomezr](https://github.com/josegomezr/the-super-tiny-compiler)
- [donaldpipowitch](https://github.com/donaldpipowitch/the-super-tiny-compiler-in-rust)





