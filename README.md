# Printf

Program Name: ft_printf

Description: ft_printf is a custom implementation of the printf() function from the C standard library. It is a project aimed at understanding variadic functions in C and developing a robust, well-structured, and extensible version of printf.

Files Included

    Makefile: Contains rules for compiling the program.
    Header Files: *.h, /.h
    Source Files: *.c, /.c

External Functions

    Memory Management: malloc, free
    Output: write
    Variable Argument List Handling: va_start, va_arg, va_copy, va_end

Requirements

    Conversions Handled: cspdiuxX%
    Buffer Management: Not implemented; differs from original printf().
    Comparison: Function will be compared against the original printf().
    Library Creation: Use ar command to create libftprintf.a; libtool is forbidden.
    Library Location: libftprintf.a to be created at the root of the repository.

Usage

    To use ft_printf in your C program, include the header file ft_printf.h and 
    link against the library libftprintf.a. The prototype of ft_printf() is 
    int ft_printf(const char *, ...). Use the same format specifiers as you 
    would with printf().

Example:
  ```c
    #include "ft_printf.h"

    int main()
    {
      ft_printf("Hello, %s!\n", "world");
      return 0;
    }
```

Building:

    To compile the program and create the library, 
    run make in the root directory of the repository. 
    This will generate libftprintf.a.
    
Cleaning:

    To remove object files and the library, run make clean. To remove all compiled files, inc
