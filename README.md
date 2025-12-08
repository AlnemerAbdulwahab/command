# Command - Simple Addition Program

Simple program that takes command-line arguments and performs basic addition operation.

## Description

This Java program takes two numbers as command-line arguments and calculates their sum.

## Prerequisites

- Java Development Kit (JDK)
- Command-line terminal or command prompt

## Compilation

Compile the program using the following command:

```bash
javac add.java
```

## Usage

Run the program by providing two numbers as arguments:

```bash
java add <num1> <num2>
```

### Example

```bash
java add 1 2
```

**Output:**
```
3
```

### Additional Examples

```bash
java add 10 25
# Output: 35

java add -5 15
# Output: 10

java add 100 200
# Output: 300
```

## Error Handling

If fewer than two arguments are provided, the program will display a usage message:

```bash
java add 5
```

**Output:**
```
Usage: add <num1> <num2>
```

## Notes

- The program expects integer values as input
- Providing non-integer values will result in a `NumberFormatException`
- Only the first two arguments are used; additional arguments are ignored

## About

This project was created as part of the Tuwaiq Academy Software Development Bootcamp.
