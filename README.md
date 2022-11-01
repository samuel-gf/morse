# Morse code sound synthesizer for command line

Here you have two shell scripts:

1. *Morsebeep* emits morse code sounds from command line.
2. *Morsetraining* is a script to train morse code every day.

## Morsebeep script

### Usage

$ morsebeep <parameters>

**Parameters**

- `-f` frequency of sound (default 880 Hz)
- `-m` message
- `-t` length of dot (default 0.05 seconds)
- `-s` shows dots and dashes in screen .... . .-.. ---    .-- --- .-. .-.. -.."
- `--help` or `-h` this help

### Requisites

This shell uses the command `play`it belongs to the `SoX`package and thera are many ways to install
it in your systema. You can try:

- Linux `sudo apt install sox`
- MacOS `brew install sox`
- Windows (I dont know, but if you find out it, please, email me)




## Morsetraining script

You can use the script `random_test` to train yourself

### Usage

**Parameters**

- `-d` dictionary_file (each line one word)"
- `-t` length of dot (default $time seconds)"
- `--help` this help"

### Examples
```
$ morsetraining -d letters.txt
```

## More resources

- [Morse code world](https://morsecode.world)
