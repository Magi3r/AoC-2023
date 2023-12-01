# AoC-2023
[Advent of Code 2023](https://adventofcode.com/2023)

Solutions written in [Der Deutschen Programmiersprache](https://github.com/DDP-Projekt/Kompilierer).

## Usage
After installing the compiler, you can compile and invoke the program like this:
```
kddp kompiliere script.ddp
./script <input.txt
```

Or run it like this:
`kddp starte script.ddp <input.text`

I chose to read the input from stdin, because the rather small stdlib of Die Deutsche Programmiersprache has more predefined functions for reading from stdin than for reading text files.