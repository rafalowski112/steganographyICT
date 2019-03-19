# steganographyICT

The main goal of the project is to develop a program, which allows hiding information in a PNG image. The algorithm was written in Python 3 language with a use of PIL module, which provides basic image operations. One symbol (8bits) is encrypted in one row of pixels, and therefore the amount of bytes of a binary file has to smaller than the length of an image. The starting point of encoding is in the right-bottom corner. Every symbol is hidden in 16 pixels. 
