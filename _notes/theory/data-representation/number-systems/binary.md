---
title: Binary
---

> - **Bit**​ - This is the name for a single binary digit (e.g. 0 or 1)​
> - **Byte**​ - A byte is the name given to 8 bits​
> - **Nibble**​ - A nibble is half a byte (4 bits)

## What is binary?
**Binary** (also known as base-2) is a number system which only uses `0s` and `1s`​.

This is a useful number system to use in computer science because a computer is made from millions of tiny components which only understand a state of `ON` or `OFF`​. Any form of data needs to be converted to binary to be processed by a computer, once in this format data is processed using [[logic gates]] and stored in small pieces of memory called [[registers]].

This means we can easily match the state of the computer to a binary value​:

- A switch set to `ON` equals `1`
- A switch set to `OFF` equals `0`

By combining millions of these `ON` and `OFF` signals together, we can program a computer to think!

This is different to **denary** (also known as base-10 or decimal), the name of the number system you use every day​, which uses the numbers 0 to 9​.

## Example of a binary number

Consider the 8-bit number `11101110`, this can be re-written in a table as follows:

| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
|-----|----|----|----|---|---|---|---|
| **1**  |  **1** |  **1** |  0 | **1** | **1** | **1** | 0 |

A place value is written above each of the bits, increasing by powers of 2 (1, 2, 4, 8, etc...). The value of this binary number can be calculated by adding together all place values where the bit is equal to 1.

`128 + 64 + 32 + 8 + 4 + 2 = 238`

## Counting in 4-bit binary

In the table below you can see all possible 4-bit binary values `0000` to `1111`, in denary this is equivalent to `0` to `15`.

| Denary value | Binary value |
|--------------|--------------|
| 0 | 0000 |
| 1 | 0001 |
| 2 | 0010 |
| 3 | 0011 |
| 4 | 0100 |
| 5 | 0101 |
| 6 | 0110 |
| 7 | 0111 |
| 8 | 1000 |
| 9 | 1001 |
| 10 | 1010 |
| 11 | 1011 |
| 12 | 1100 |
| 13 | 1101 |
| 14 | 1110 |
| 15 | 1111 |
