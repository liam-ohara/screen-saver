# Screensaver
This application was written as a simple demonstration of string concatenation, and looping forwards and backwards through an array in GW-BASIC.

When run, this application will print a sequence of `X` characters to the screen starting from the top left and ending at the bottom right, before reversing direction. The program will loop infinitely until the user presses a character key. Each `X` is printed on its own line preceded by an increasing or decreasing amount of whitespace.

## Installation
### Prerequisites
* BASIC interpreter compatible with GW-BASIC/BASICA dialects of BASIC (![PC-BASIC](http://robhagemans.github.io/pcbasic/) is a cross-platform interpreter)

### Installation
1. Download `scrsvr.bas` from the `/src/` directory.
2. Move the downloaded file to another local directory on your device of your choosing.
3. Open your BASIC interpreter and using the `CHDIR` command, change the current working directory to the local path of `scrsvr.bas`.
4. Type `LOAD"scrsvr.bas` to load the code into the interpreter.
5. Type `LIST` to confirm the code has loaded.
   
## Usage
Once you have loaded `scrsvr.bas` into your BASIC interpreter, type `RUN` to run the screensaver program.
To end the program, press any character key. If unresponsive, press `CONTROL + C` to force the interpret to stop.
