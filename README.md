# PRINTF PROYECT IN C👩‍💻

¿What is printf?
Printf is the function we use to make a formatted printout. 
Printf= the f stands for input by formatted output

# EXAMPLE IN C:👇

	  printf("Color: %s, Number1: %d, Number2: %05d, Hexadecimal: %x, Real: %5.2f.\n", "red", 12345, 89, 255, 3.14);
will print the following line (including the newline character \n):

	 Color: red, Number1: 12345, Number2: 00089, Hexadecimal: ff, Real: 3.14.

# Requirements📌
- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All your files should end with a new line
- A README.md file, at the root of the folder of the project is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You are not allowed to use global variables
- No more than 5 functions per file
- In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
- The prototypes of all your functions should be included in your header file called main.h
- Don’t forget to push your header file
- All your header files should be include guarded
- Note that we will not provide the _putchar function for this project

## Resources📚
(Secrets of printf)[https://holbertonintranet.s3.amazonaws.com/uploads/misc/2022/11/d38f88e96a617135804dca9f9c49632751e06aa7.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20221118%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20221118T213113Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0d62b00df270eb583a92b9609c78d34fbc961993ec081ef7470de0da1d301574]
*Man or help*
- write (man 2 write)
- malloc (man 3 malloc)
- free (man 3 free)
- va_start (man 3 va_start)
- va_end (man 3 va_end)
- va_copy (man 3 va_copy)
- va_arg (man 3 va_arg)

# Compilation💻
- Your code will be compiled this way:
		$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -Wno-format *.c
		
## Format Specifiers!
The flags in the format string must have the following structure (fields in square brackets are optional):

	%[parameter][flags][width][.precision][length]type
|function name   | Description |
| ------------ | ------------ |
| %d %i | Signed decimal conversion of an integer |
| %c |   Prints the corresponding ASCII character |
| %x %X | Unsigned hexadecimal conversion  |
| %e %E | Signed floating point conversion to scientific notation  |
| %f F | Conversion to signed floating point, using decimal point  |
| %g %G |   Conversion to floating point, using the notation requiring the least amount of space |
| %o | Unsigned octal conversion of an integer
| %u | Unsigned decimal conversion of an integer  |
| %s | Character string (ending with '\0')  |
| %% | Prints the symbol % |



# Flow chart📊


##  AUTHORS🖊
Nathaly Ortiz.
Charline Mosquera.
Yurany Ulchur.
