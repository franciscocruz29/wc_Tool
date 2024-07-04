# ccwc - Word Count Tool

A lightweight implementation of the Unix 'wc' (word count) utility, written in C.

## Description

ccwc (Coding Challenge Word Count) is a clone of the classic Unix 'wc' command. It's implemented in C and designed to count bytes, lines, words, and characters in text files or from standard input.

## Features

- Count bytes in a file (-c option)
- Count lines in a file (-l option)
- Count words in a file (-w option)
- Count characters in a file (-m option)
- Support default behavior (equivalent to -c, -l, and -w options)
- Read from standard input when no filename is specified

## Usage

Options:

- `-c`: Print the byte count
- `-l`: Print the line count
- `-w`: Print the word count
- `-m`: Print the character count

If no options are specified, it's equivalent to using -c, -l, and -w options together.
