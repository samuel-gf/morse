# Morse code sound synthesizer for command line

This easy shell cript emits morse code sounds from command line

## Usage

$ morsebeep <parameters>

**Parameters**

- `-m` message
- `-t` length of dot (default 0.05 seconds)
- `-f` frequency of sound (default 880 Hz)
- `--help` or `-h` this help

## Requisites

This shell uses the command `play`it belongs to the `SoX`package and thera are many ways to install
it in your systema. You can try:

- Linux `sudo apt install sox`
- MacOS `brew install sox`
- Windows (I dont know, but if you find out it, please, email me)
