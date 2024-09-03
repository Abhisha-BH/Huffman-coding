In this project,we implement the Huffman Coding Algorithm
This repository contains the following source code and data files:
'Huffman.c'-C programming language implementation
'message.txt'-A small text message file for testing
'Makefile'-For compiling the source

Usage:
To run the algorithm on the supplied example data,first compile
$make
and then run the program:
$./huffman encode message.txt encoded.dat
$./huffman decode encoded.dat decoded.txt
$diff decoded.txt message.txt
