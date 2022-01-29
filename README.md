# 42 - FT_PRINTF PROJECT

### Introduction
The versatility of the printf function in C represents a great exercise in programming for us. This project is of moderate difficulty. It will enable you to discover variadic functions in C.

## Mandatory Part
A brief description of the required conversions:
* %c print a single character
* %s print a string of characters
* %p the void * pointer argument is printed in hexadecimal
* %d print a decimal (base 10) number
* %i print an integer in base 10
* %u print an unsigned decimal (base 10) number
* %x print a number in lowercase hexadecimal (base 16)
* %X print a number in uppercase hexadecimal (base 16)
* %% print a percent sign

Complete references can be found in: **man 3 printf / man 3 stdarg**

### Technical Considerations
* The prototype of ft_printf should be **int ft_printf(const char \*, ...);**
* You have to recode the libc's printf function
* It must not do the buffer management like the real printf
* It will manage the following conversions: cspdiuxX\%
* It will be compared with the real printf
* You must use the command ar to create your library, using the command libtool is forbidden

## Bonus Part
* Manage any combination of the following flags '-0.' and minimum field width with all conversions
* Manage all the following flags: '# +' (yes, one of them is a space)
