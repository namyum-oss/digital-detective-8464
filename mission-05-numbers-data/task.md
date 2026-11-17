# Mission 5 — Numbers and Data

## Task 5.1 — Convert numbers by hand

| Question | Your working and answer |
|---|---|
| Convert decimal 13 to binary. | 13 ÷ 2 = 6 R1<br>6 ÷ 2 = 3 R0<br>3 ÷ 2 = 1 R1<br>1 ÷ 2 = 0 R1<br>Reading remainders upwards: **1101₂** |
| Convert decimal 25 to binary. | 25 ÷ 2 = 12 R1<br>12 ÷ 2 = 6 R0<br>6 ÷ 2 = 3 R0<br>3 ÷ 2 = 1 R1<br>1 ÷ 2 = 0 R1<br>Reading remainders upwards: **11001₂** |
| Convert binary 1010 to decimal. | (1 × 2³) + (0 × 2²) + (1 × 2¹) + (0 × 2⁰)<br>= 8 + 0 + 2 + 0<br>= **10₁₀** |
| Convert binary 1101 to decimal. | (1 × 2³) + (1 × 2²) + (0 × 2¹) + (1 × 2⁰)<br>= 8 + 4 + 0 + 1<br>= **13₁₀** |
| Convert hexadecimal A to decimal. | A = 10<br>10 × 16⁰<br>= **10₁₀** |
| Convert hexadecimal 1F to decimal. | (1 × 16¹) + (15 × 16⁰)<br>= 16 + 15<br>= **31₁₀** |
| Convert binary 1111 to hexadecimal. | 1111₂ = 8 + 4 + 2 + 1<br>= 15<br>15 = F in hexadecimal<br>Answer: **F₁₆** |

## Task 5.2 — Verify using Python

| Conversion | Python expression | Result | Matches manual calculation? |
|---|---|---|---|
| Decimal 13 to binary | `bin(13)` | `0b1101` | Yes |
| Decimal 25 to binary | `bin(25)` | `0b11001` | Yes |
| Decimal 42 to binary | `bin(42)` | `0b101010` | Yes |


### Explanation

- `int()` converts the input string into an integer.
- `bin()` converts an integer into its binary representation.
- `hex()` converts an integer into its hexadecimal representation.
- `print()` displays the converted values.

### Task 5.3 — Test results

The program was tested with three different positive decimal numbers.

| Test number (Decimal input) | Binary output | Hexadecimal output |
|---:|---|---|
| 13 | `0b1101` | `0xd` |
| 25 | `0b11001` | `0x19` |
| 42 | `0b101010` | `0x2a` |

### Explanation of conversion functions

- `bin()` converts a decimal integer into its binary representation.
- `hex()` converts a decimal integer into its hexadecimal representation.

## Task 5.4 — How is text stored?

### 1. Find the ASCII decimal codes for uppercase A and lowercase a.

- Uppercase A = **65**
- Lowercase a = **97**

### 2. Explain why a computer needs an encoding standard to store text.

A computer stores information as binary data, so it needs an encoding standard to represent characters using numbers. This allows different devices and programs to interpret stored text consistently.

### 3. Name one example of a character that is not part of basic ASCII.

The Indian Rupee symbol (₹) is not part of basic ASCII. It can be represented using Unicode encoding standards such as UTF-8.
