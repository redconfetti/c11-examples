# C11 Examples

Code examples from Sams Teach Yourself C Programming in One Hour a Day (Seventh Edition)

Covers ANSI C11 Standard.

## C Examples

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
[GNU Auto-unit](http://autounit.tigris.org/) or [C Unit](http://cunit.sourceforge.net/)

## Page Reference

* Listing 2-1 - Page 24
* Listing 2-2 - Page 30
* Listing 3-1 - Page 42
* Listing 3-2 - Page 51
* Listing 4-1 - Page 63
* Listing 4-2 - Page 66
* Listing 4-3 - Page 73
* Listing 4-4 - Page 75
* Listing 4-5 - Page 78
* Listing 4-6 - Page 83
* Listing 5-1 - Page 92
* Listing 5-2 - Page 101
* Listing 5-3 - Page 104

## Reference

* [Notes](docs/notes.md)
* [Beginner's Guide to Linkers](https://www.lurklurk.org/linkers/linkers.html)
