---
title: Test data
---

> - **Valid**​ - Test data the values that your program expects.
> - **Invalid**​ - Test data values your program does not expect.
> - **Extreme**​ - The limits of valid data (i.e. smallest and largest valid values).
> - **Boundary**​ - An extension of extreme data to also include the neighbouring invalid values.

## Why test programs

Before any software can be released it needs to be thoroughly checked. Software testing allows programmers to prove that their programs work as designed. If there are any bugs present in program, testing allows us to find and fix them ahead of time.

## How to test programs

There are for main categories of data that can be used in order to test a program:

- **Valid**: Data that the program should expect and accept
- **Invalid**: Data that the program should not accept
- **Extreme**: The minimum input that should be accepted and the maximum input that should be accepted
- **Boundary**: This data is very similar to extreme data, but also includes the invalid values directly next to the extreme values

## Simple example

Imagine this simple program:

> Ask the user to enter a number between 1 and 10.
>
> If the number is within the range, multiply by 2 and return the value. Else, return an error message.

The following tests show an example of suitable data which covers **valid**, **invalid**, **extreme** and **boundary** inputs.

| Test data | Type of test data | Expected program output | 
|-----------|-------------------|-----------------|
| 2 | Valid | 4 |
| 5 | Valid | 10 |
| 7 | Valid | 14 |
| 8 | Valid | 16 |
| -20 | Invalid | Error message - input out of range |
| 100 | Invalid | Error message - input out of range |
| "ten" | Invalid | Error message - incorrect input data type |
| 1 | Valid (Extreme) | 2 |
| 10 | Valid (Extreme) | 20|
| 0 | Invalid (Boundary) | Error message - input out of range |
| 11 | Invalid (Boundary) | Error message - input of of range |