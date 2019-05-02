# C11 Examples
Code examples from Sams Teach Yourself C Programming in One Hour a Day (Seventh Edition)

Covers ANSI C11 Standard.

# C Examples

ANSI C examples from
[Sams Teach Yourself C Programming in One Hour a Day (Seventh Edition)](https://www.amazon.com/Sams-Teach-Yourself-Programming-Hour/dp/0789751992/) 
by Bradley L. Jones, Peter Aitken, and Dean Miller.

Examples adapted for use with [GCC](https://en.wikipedia.org/wiki/GNU_Compiler_Collection), developed and tested on Mac OS X.

Some examples provided to further clarify my own understanding of
how certain methods operate.

## Installation

To make use of these examples, you'll need to install `gcc` and `make`.

### Linux

```shell
sudo apt-get install gcc
sudo apt-get install make
```

### Mac

```shell
brew install gcc
brew install make
```

## Makefiles

A utility known as `make` automates the process of compiling your
C code into an executable file. It is designed to simplify very complex
compilation processes. I am using it here to simplify even
the simple process of compiling these examples.

When a directory has a `Makefile` present, the `make` utility
uses the configuration inside of the `Makefile` to perform certain tasks.

Tasks:
* `make` - Compiles the 'main' executable into machine code in the current directory
* `make clean` - Deletes the 'main' executable from the current directory

## Unit Testing

Eventually I want to implement unit testing of C Code with
[GNU Autounit](http://autounit.tigris.org/) or [C Unit](http://cunit.sourceforge.net/)

## Reference

See [Notes](docs/notes.md)