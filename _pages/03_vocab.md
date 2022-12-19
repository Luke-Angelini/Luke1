---
layout: page
title: Vocab
permalink: /vocab/
---

## General Vocab list:

1. Markdown: A file type for simple text formats
2. Python: A general-purpose programming language

## Powershell:

1. cd = change directory
2. cd ~ = change directory to home
3. ls = list files
4. code. = opens VScode

## Markdown Vocab list:

1. #, ## Changes size of font
2. *italics*
3. **bold**
4. ~~strikethrough~~

# Python Vocab List:

1. Def: Defines a function
2. Print: Prints the inputted text
3. If: Performs an action if a condition is true
4. Else: Performs an action if a condition is not true
5. String: A series of characters
6. Boolean: A value that is either true of false

# Unit 2 - Binary/Data Terms

Bits and Bytes:

Bits and Bytes are binary digits, or bits for short
Single Bits are too small to be much use, so they are grouped together into units of 8 bits.
Each 8-bit unit is called a byte
Hexadecimals/Nibbles:
Hexadecmial is a base-16 numbering system that uses the digits 0 through 9 and the letters A through F to represent data, including nibbles and bytes
Nibbles can be represented by a hexadecimal digit
Bits: A bit or a binary digit, is the smallest unit of data that a computer can process and store. A bit can be one of 2 physical states, such as either 0 or 1, yes or no, and true or false.

Bytes: A byte is a unit of data that is eight bits long. It is used by computers to represent a character such as a letter or number symbol.

Hexadecimal: Hexadecimal is a numbering system with base 16. There are 16 symbols or possible digit values from 0 to 9, followed by six alphabetic characters -- A, B, C, D, E and F. It can be used to represent large numbers with fewer digits.

Binary Numbers

Unsigned Integer: Numbers without + or - sign, only representing the magnitude not the direction. Used when we know that the value we are storing will always be non-negative

Ex. 1, 2, 3, 4

Signed Integer: The default where the variable can hold positive or negative numbers

Ex. -1, 6, -29, 1000

Floating Point: Positive or negative whole number with a decimal point. Used to represent real numbers and is written with a decimal point dividing the integer and fractional parts

Ex. 1.23, 87.425, and -9039454.2, NOT 101, -3, 18203

Binary Data Abstractions:

Boolean: Variable type that represents one of two values: True or False.

A = 200

B = 33

If b > a:

print(“b is greater than a”)

If a > b:

print(“a is greater than b”)

ASCII: Stands for American Standard Code for Information Interchange. ASCII was first created when all people wanted computers to be able to show was numbers, letters, punctuation, and non-printing commands(Enter, Delete, F1).. All ASCII encoded character can be represented by 1 byte, or 8 bits for a total of 2^8 = 127 different total characters.

Ex. lowercase “h” character → 104 (D) → 01101000(B)

* Unicode: today, people use emojis and new symbols like other languages and stuff and computers needed to be able to represent all that. 

Unicode is a new standard defining an association between characters and even more numbers. Each unicode character (utf8) is 4 bytes, or 32 bits, enough for 2^32 different characters. Most modern programming languages represent strings as utf8 encoded characters (hex) because people use these new symbols in their code, but old languages like C still associat either character type with a single byte integer

RGB: RGB (red, green, and blue) refers to a system for representing the colors to be used on a computer display.These 3 colors can be combined in various proportions to obtain any color in the visible spectrum.

Ex. rgb(255, 0, 0) = red because red is set to its highest value (255), and the other two (green and blue) are set to 0.

Data Compression

Lossy: a techinique that reduces file size by discarding less important information

Lossless (unit 3): Every bit of data originally in a file remains after it is uncompressed, and all the information is restored.

Variables:An abstraction inside a program that holds a specific value or meaning defined by the programmer.

Data Types:

Integer- highScore (involves math, save as integer or numbers)

String- firstName (name is text, so it is a string)

Boolean- isSunny (2 options, true or false)

String- phoneNumber (no math, just numbers)

