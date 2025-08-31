# Chapter 1 – Basics
**Topic:** Variables, data types, operators  
**Difficulty:** ⭐  

## 1. Variables
Variables store data in memory.  
Syntax example:

```c
int age = 25;
float pi = 3.14;
char letter = 'A';
```
## 2. Data Types

- `int` – whole numbers, e.g., 42
- `long` / `long long` – larger integers
- `char` – single character
- `char*` – string (pointer to char array)
- `float` / `double` – decimal numbers
- `unsigned` variants – only positive numbers

## 3. Constants
const int x = 5; /* value cannot change */

## Operators

### Arithmetic Operators
Basic math operations.

- `+` : addition  
- `-` : subtraction  
- `*` : multiplication  
- `/` : division  
- `%` : modulo (remainder)

**Example:**
```c
int a = 5 + 3;  // 8
int b = 10 % 3; // 1
```
### Comparison Operators
Compare values, result is 0 (false) or 1 (true).
- `==` : equal to
- `!=` : not equal to
- `<` : less than
- `>` : greater than
- `<=` : less than or equal to
- `>=` : greater than or equal to

Example:

```c
int x = 5;
int y = 10;
int result = x < y; // 1 (true)
```
### Logical Operators
Combine or negate boolean values (0 = false, non-zero = true).
- `&&` : AND
- `||` : OR
- `!` : NOT

Example:
```c
int a = 1;  // true
int b = 0;  // false
int c = a && b; // 0 (false)
int d = !b;     // 1 (true)
```
### Assignment Operators
Assign values to variables, optionally combined with arithmetic.

- `=` : simple assignment
- `+=` : add and assign
- `-=` : subtract and assign
- `*=` : multiply and assign
- `/=` : divide and assign
- `%=` : modulo and assign

Example:

```c
int z = 5;
z += 3; // z = z + 3 → 8
```

## Practice Challenge

Declare variables of each type.
Perform some arithmetic and print the results.
