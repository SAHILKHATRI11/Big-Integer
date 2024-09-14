# Big Integer Library

## Overview
This project implements a Big Integer library in C, allowing for arithmetic operations on integers of arbitrary size. It overcomes the limitations of standard data types like `int` or `long` by using arrays to represent big numbers. The library supports basic operations such as addition, subtraction, multiplication, and division on these big integers.

## Features
- **Addition**: Add two big integers.
- **Subtraction**: Subtract one big integer from another.
- **Multiplication**: Multiply two big integers.
- **Division**: Perform division on two big integers.

## How it Works
The big integers are represented as arrays of digits, where each index of the array corresponds to a digit of the number. Operations are performed digit by digit, similar to how you would do long-hand arithmetic.

## Supported Operations
1. **Addition**:
   - Add two large integers stored as arrays.
2. **Subtraction**:
   - Subtract a large integer from another, handling negative results as well.
3. **Multiplication**:
   - Multiply two large integers using digit-by-digit multiplication.
4. **Division**:
   - Divide two large integers to obtain both quotient and remainder.

## Files
- `BigInteger.c`: Contains the implementation of all arithmetic operations on big integers.
- `BigInteger.h`: Header file with function declarations for the library.

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/SAHILKHATRI11/Big-Integer.git
    ```
2. Compile the program:
    ```bash
    gcc BigInteger.c -o biginteger
    ```
3. Run the program:
    ```bash
    ./biginteger
    ```

## Future Improvements
- Implement additional operations like modulus, power, and GCD for big integers.
- Add support for floating-point numbers.

## License
This project is licensed under the MIT License.
