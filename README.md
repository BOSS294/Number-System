### Number Systems: Overview

**Number systems** are methods for representing numbers using symbols or digits. The most common number systems used in computing and digital electronics include:

1. **Decimal (Base-10)**:
   - Uses digits 0-9.
   - Each position represents a power of 10.
   - Example: \( 123_{10} = 1 \times 10^2 + 2 \times 10^1 + 3 \times 10^0 \).

2. **Binary (Base-2)**:
   - Uses digits 0 and 1.
   - Each position represents a power of 2.
   - Example: \( 101_2 = 1 \times 2^2 + 0 \times 2^1 + 1 \times 2^0 \).

3. **Octal (Base-8)**:
   - Uses digits 0-7.
   - Each position represents a power of 8.
   - Example: \( 75_8 = 7 \times 8^1 + 5 \times 8^0 \).

4. **Hexadecimal (Base-16)**:
   - Uses digits 0-9 and letters A-F (where A=10, B=11, ..., F=15).
   - Each position represents a power of 16.
   - Example: \( 1A_{16} = 1 \times 16^1 + 10 \times 16^0 \).

### Conversion Chart

| Decimal | Binary | Octal | Hexadecimal |
|---------|--------|-------|-------------|
| 0       | 0000   | 0     | 0           |
| 1       | 0001   | 1     | 1           |
| 2       | 0010   | 2     | 2           |
| 3       | 0011   | 3     | 3           |
| 4       | 0100   | 4     | 4           |
| 5       | 0101   | 5     | 5           |
| 6       | 0110   | 6     | 6           |
| 7       | 0111   | 7     | 7           |
| 8       | 1000   | 10    | 8           |
| 9       | 1001   | 11    | 9           |
| 10      | 1010   | 12    | A           |
| 11      | 1011   | 13    | B           |
| 12      | 1100   | 14    | C           |
| 13      | 1101   | 15    | D           |
| 14      | 1110   | 16    | E           |
| 15      | 1111   | 17    | F           |

### Conversion Steps

#### Decimal to Binary
1. **Divide the decimal number by 2.**
2. **Record the remainder.**
3. **Use the quotient for the next division.**
4. **Repeat until the quotient is 0.**
5. **The binary representation is the remainders read from bottom to top.**

#### Decimal to Octal
1. **Divide the decimal number by 8.**
2. **Record the remainder.**
3. **Use the quotient for the next division.**
4. **Repeat until the quotient is 0.**
5. **The octal representation is the remainders read from bottom to top.**

#### Decimal to Hexadecimal
1. **Divide the decimal number by 16.**
2. **Record the remainder (0-15).**
3. **Use the quotient for the next division.**
4. **Repeat until the quotient is 0.**
5. **The hexadecimal representation is the remainders read from bottom to top, where 10=A, 11=B, ..., 15=F.**

#### Binary to Decimal
1. **Multiply each binary digit by 2 raised to the power of its position (starting from 0 on the right).**
2. **Sum the results.**

#### Binary to Octal
1. **Group the binary digits into sets of three, starting from the right (add leading zeros if necessary).**
2. **Convert each group of three binary digits to its octal equivalent.**

#### Binary to Hexadecimal
1. **Group the binary digits into sets of four, starting from the right (add leading zeros if necessary).**
2. **Convert each group of four binary digits to its hexadecimal equivalent.**

#### Octal to Decimal
1. **Multiply each octal digit by 8 raised to the power of its position (starting from 0 on the right).**
2. **Sum the results.**

#### Octal to Binary
1. **Convert each octal digit to its 3-bit binary equivalent.**

#### Octal to Hexadecimal
1. **Convert octal to binary.**
2. **Group binary digits into sets of four.**
3. **Convert each group to hexadecimal.**

#### Hexadecimal to Decimal
1. **Multiply each hexadecimal digit by 16 raised to the power of its position (starting from 0 on the right).**
2. **Sum the results.**

#### Hexadecimal to Binary
1. **Convert each hexadecimal digit to its 4-bit binary equivalent.**

#### Hexadecimal to Octal
1. **Convert hexadecimal to binary.**
2. **Group binary digits into sets of three.**
3. **Convert each group to octal.**

These methods provide a structured approach to convert between different number systems, using the properties and powers of each base system to simplify the conversion process.
