# Chapter 2 – Control Flow
**Topic:** Conditional statements and loops
**Difficulty:**⭐⭐

## Conditional Statements

### `if` statement
Executes a block if the condition is true.

```c
int x = 10;
if (x > 5) {
    // This runs because x > 5
    printf("x is greater than 5\n");
}
```

### `if-else` statement
Executes one block if true, another if false.

```c
int x = 3;
if (x > 5) {
    printf("x is greater than 5\n");
} else {
    printf("x is 5 or less\n");
}
```
### `else if`
Chain multiple conditions.

```c
int x = 7;
if (x > 10) {
    printf("x is greater than 10\n");
} else if (x > 5) {
    printf("x is greater than 5 but <= 10\n");
} else {
    printf("x is 5 or less\n");
}
```
### `switch` statement
Choose between multiple cases based on a value.

```c
int day = 3;
switch(day) {
    case 1:
        printf("Monday\n");
        break;
    case 2:
        printf("Tuesday\n");
        break;
    case 3:
        printf("Wednesday\n");
        break;
    default:
        printf("Another day\n");
        break;
}
```
## Loops
### `for` loop
Repeat a block a fixed number of times.

```c
for (int i = 0; i < 5; i++) {
    printf("%d\n", i);
}
```
### `while` loop
Repeat as long as a condition is true.

```c
int i = 0;
while (i < 5) {
    printf("%d\n", i);
    i++;
}
```
### `do-while` loop
Execute at least once, then repeat while condition is true.

```c
int i = 0;
do {
    printf("%d\n", i);
    i++;
} while (i < 5);
```

## Practice Challenge

1. Declare an `int`, `char`, and `float` variable.
2. Use an `if-else` statement to check if the integer is positive, negative, or zero, and print a message.
3. Create a `for` loop that prints numbers from 1 to 10.
4. Write a `switch` statement that prints the name of the day for a variable `int day` (1–7).
5. Bonus: Use a `while` loop to count down from 5 to 1 and print each number.
```
