# 0x11. C - printf

## Contributors

1. [Mbiaha Rodrigue](https://github.com/rodriguembiabo)
2. [Yonga Yonga Gaelle Manuella](https://github.com/yongagaelle)

## About
An introductory project on:
- functions and how to use them
- the difference between a declaration and a definition of a function
- prototypes
- scope of variables
## File Descriptions
### Mandatory
**[_printf.c](_printf.c)** - Prints a string to the standard output, according to a given format
**[_put.c](_put.c)** - converts a number according to the base passed as a parameter
**[convert.c](convert.c)** - converter function
**[convert_number.c](convert_number.c)** - prints unsigned hex numbers in lowercase
_put.c converter function convert_number.c
**[main.h](main.h)** -
**[man_3_printf](man_3_printf)** -
**[params.c](params.c)** -
**[print-functions.c](print-functions.c)** -
**[print-number.c](print-number.c)** -
**[simple-printers.c](simple-printers.c)** -
**[specifier.c](specifier.c)** -
**[string_fields.c](string_fields.c)** -
## Usage
- Prints a string to the standard output, according to a given format
- All files were created and compiled on Ubuntu 20.04 using gcc with the command gcc -Wall -Werror -Wextra -pedantic -std=gnu89
- Returns the number of characters in the output string on success, -1 otherwise
- Call it this way: _printf("format string", arguments...) where format string can contain conversion specifiers and flags, along with regular characters
## Examples
- _printf("Hello, Rodrigue and Gaelle\n") prints "Hello, Rodrigue and Gaelle", followed by a new line
- _printf("%s", "Hello") prints "Hello"
- _printf("This is a number: %d", 98) prints "This is a number: 98"