# Advent of Code 2019 in Carml
Solutions written in my own homebrew programming language Carml -- they actually work! :-)

# Run
First, install a build of carml
```bash
> git clone git@github.com:georgek42/carml.git
> cd carml && make && make install
```
Then you can run the solutions from the Carml REPL (`cl`)
```bash
> cl
Carml 0.0.1
Type ":help" for more information

>>> :help 

Type ":stmt" to enter statement mode
Type ":expr" to enter expression mode
Type ":load <filename>" to load a file into the current environment

You are in auto mode
>>> :load aoc_day1.carml
>>> solve ((): unit);;
4974073
```
