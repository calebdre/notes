# Binary Conversion - 1/28

[conversion table](http://www.rapidtables.com/convert/number/how-hex-to-binary.htm)

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

#### Base 10 Conversion
- convert 10 base 10 to binary
    + take the modulus of 2 and the divide by 2. Get the remainder and add to the binary value and then take the dividend and as the next number
    + 10 % 2 = 0, 10 / 2 = 5
    + 5 % 2 = 1, 5 / 2 = 2
    + 2 % 2 = 0, 2 / 2 = 1
    + 1 % 2 = 1, 1 /2 = 0
    + answer: 0101

- convert 1011 to base 10
    + (1 * 2^3) + (0 * 2^2) + (1 * 2^1) + (1 * 2^0)
    + 8 + 0 + 2 + 1
    + 11

#### Negative Binary Numbers
- represent -2 as a binary number
    + 1010 (it's notmall 0010, but the 1 at the front makes it a negative number)
- add: -3 + -2
    + 1101
- add: 7 + -5
    + 0010
- convert -28 to binary
    - find out 28: 00011100
    - invert the digits: 11100011
    - add 1 (0001)
    - 11100100

questions:
- when would you need to use Two's compliment (to find the inverse)?
- how would you write -8? (becacuse it begins with 1)
- how would you add -5 + -6? -9 + -9?


### Binary Fractions
- convert 101.1101 to decimal
    + numbers to the right of decimal are to the negative power
    + (1 * 2^2) + (0 * 2^1) + (1 * 2^0) + (1 * 2^-1) + (1*2^-2) + (0 * 2^-3) * (1 * 2^-4)  = 5.8125
- convert 111.111 to decimal
    + (1 * 2^2) + (1 * 2^1) + (1 * 2^0) + (1 * 2^-1) + (1 * 2^-2) + (1 * 2^-3) = 7.875
- convert 13.6875 to binary
    + separate the number from the left and right
    + 13 to binary = 1101
    + for .6875, instead of dividing by 2, multiply by 2 (also, read down)
    + so .6875 to binary is 1011
    + 1101 1011

+ convert 32.45 to binary
    + 32 / 2 -> 16,0 | 16 / 2 -> 8,0 | 8 / 2 -> 4,0 | 4 / 2 -> 2 | 2 / 2 -> 1,0 | 1 / 2 -> 0 , 1 = 100000
    + .45 * 1 -> 0.9 | .9 * 2 = 1.8,

+ convert 53 to hex
    + 
+ convert 19
    +
