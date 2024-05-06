# Huffman Coding Compression and Decompression

## Overview
This program demonstrates file compression and decompression using Huffman coding algorithm in Python.

## Features
- Compresses a text file using Huffman coding algorithm.
- Decompresses the compressed binary file back to its original text format.

## How it works
### Compression
1. Reads the input text file to be compressed.
2. Calculates the frequency of each character in the text.
3. Builds a Huffman tree based on the character frequencies.
4. Generates Huffman codes for each character.
5. Encodes the input text using the generated Huffman codes.
6. Pads the encoded text to make its length a multiple of 8.
7. Converts the padded binary text into a byte array.
8. Writes the byte array into a binary file.

### Decompression
1. Reads the compressed binary file.
2. Converts the binary file into a bit string.
3. Removes padding from the bit string.
4. Decodes the bit string using the Huffman tree.
5. Writes the decoded text into an output text file.

## Usage
1. Compile the `Huffmancoding.ipynb` file using a C++ compiler.
2. Run the compiled executable.
3. Enter the path of the text file you want to compress.
4. The program will generate a compressed binary file with extension `.bin`.
5. The program will also generate a decompressed text file with suffix `_decompressed.txt`.

## Example
Suppose you have a text file named `input.txt` containing the text "hello world". 
1. Run the program and enter the path of `input.txt`.
2. The program will compress `input.txt` and generate `input.bin`.
3. It will then decompress `input.bin` and generate `input_decompressed.txt`.
4. The content of `input_decompressed.txt` will be "hello world".

## Flowchart

   1. --> {Compression};
   2. --> [Calculate Character Frequencies];
   3. --> [Build Huffman Tree];
   4. --> [Generate Huffman Codes];
   5. --> [Encode Text];
   6. --> [Pad Encoded Text];
   7. --> [Convert to Byte Array];
   8. --> [Write to Binary File];
   9. --> [Compressed Binary File];
   10. --> {Decompression};
   11. --> [Read Compressed Binary File];
   12. --> [Convert to Bit String];
   13. --> [Remove Padding];
   14. --> [Decode using Huffman Tree];
   15. --> [Write Decompressed Text];
   16. --> [Decompressed Text File];



asdfsfdaf
