# Spectral Test code from Knuth pseudocode


This implenents Knuth's alogrithm beginning on page 102 of his book:  
  "The Art of Computer Programming, 3rd Ed., Vol. 2: Seminumerical Algorithms, 1998"
  
The original program was wrote in assebly code by Knuth. A pseudo code of it can be found on the page 102 of the book:
// photo of pseaudocode

This code was wrote many years ago and some of the possible problems that one can encounter when writting the program are:
* Possible overflow and infinite errors when working with big integer numbers.
* Goto expressions were depricated from Python to enhance flow and readibility of code. This meas the pseudocode must be implemented in a slighly different way to work around this change.

Notes:
The code uses pure python intead of using numpy or pytorch to create vectors and matrices. This is due a an overflow problem when using pyTorch and numpy when using big numbers.
