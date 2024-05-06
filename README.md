# printf Project

## Project Overview
This project is a custom implementation of the C standard library function `printf`. This implementation replicates the basic functionality of the original `printf` function, handling various format specifiers for printing different types of data.

## Features
- Supports printing different data types including integers, floating-point numbers, characters, and strings.
- Handles common format specifiers such as `%d`, `%s`, `%c`, `%f`, and `%x`.
- Simple and lightweight implementation suitable for educational purposes or embedded systems.

## How to Use
1. Clone this repository to your local machine.
2. Include the `printf.h` header file in your C projects.
3. Use the function `ft_printf()` just like you would use the standard `printf()` function.

```c
#include "printf.h"

int main() {
    ft_printf("Hello, %s!", "world");
    return 0;
}
