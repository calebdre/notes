# Binary Conversion - 1/28

Convert a decimal to binary
1. divide the value by two and record the remainder
2. As long as the quotient obtained is not zero, continue to divide the newest quotient by two and record the remainder
3. now that a quotient of zero has been obtained, the binary rep. of the original value consists of the remainders listed from right to left in the order they were recorded

convert 128
- 128 / 2 = 64 r 0
- 64 / 2 = 32 r 0
- 32 / 2 = 16 r 0
- 16 / 2 = 8 r 0
- 8 / 2 = 4 r 0
- 4 /2 = 2 r 0
- 2 /2 = 0 r 0
- 0 / 2 = 0

convert 207
- 207 / 168 = 1 r 79
- 79 / 64 = 1 r 15
- 15 / 32 = 0 r 0
- 8 / 15 = 1 r 7
- 7 / 4 = 1 r


### Binary Math
- 1 + 1 = 10
- 1 + 1 + 1 = 11
- Or you could change binary to decimal, add them, then change decimal back to binary

### Hexidecimal Conversion
- Deals with letters and numbers
- Range is from A-F
    + where A is 10 and F is 15
- Convert 13F to Decimal
    + 1 * 16^2 + 3 * 16^1 + 15^0
- Convert Bc12
    + 11 * 16^3 + 12 * 16^2 + 1 * 16^1 +  2 * 16^0
- Convert 4DA9 to Binary
    + 0100 1101 1010 1001
- Convert 1001 0001 0011 1111
    + 913F
