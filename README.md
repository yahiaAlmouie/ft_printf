*This project has been created as part of the 42 curriculum by yahiaAlmouie*

# Description: 
The goal of this project is to recreate the behavior of the standard printf() function from the C standard library.
The project focuses on variadic functions, format parsing, recursion, and working with different data types in C.
Supported conversions The implementation supports the following conversions:

* %c — character
* %s — string
* %p — pointer address
* %d — decimal integer 
* %i — integer 
* %u — unsigned decimal integer 
* %x — lowercase hexadecimal 
* %X — uppercase hexadecimal 
* %% — percent sign
## Project structure 

```text
ft_printf/
├── ft_printf.c
├── ft_printf.h
├── print_char.c
├── print_str.c
├── print_digit.c
├── print_hex.c
├── print_pointer.c
├── Makefile
└── libft/The project uses my Libft library
```
# Instructions: 
To compile and run this project use these cmmands:

- `make`: This creates libftprintf.a
- `make clean`: Clean object files
- `make fclean`: Remove all generated files
- `make re`: Recompile from scratch

# Resources:
- [w3schools](w3schools.com)
- Tutorials from Youtube

### AI was used to explain some concepts, and help me in debugging in some parts of the code.
