<p align="end">
  <strong>🌐 Change language:</strong><br>
  <a href="/README.es.md">
   <img src="https://github.com/Nachopuerto95/multilang/blob/main/ES.png" alt="Español" width="50">
 </a>&nbsp;&nbsp;&nbsp;
 <a href="/README.md">
   <img src="https://github.com/Nachopuerto95/multilang/blob/main/EN.png" alt="English" width="50">
 </a>
</p>

# Libft (42cursus)

<img src="https://github.com/Nachopuerto95/multilang/blob/main/42-Madrid%20-%20Edited.jpg">

## 📜 About Project
> As the first project of the cursus, it is meant to familiarize us with various functions and how they are designed internally.

```html
	🚀 We will solidify our knowledge of C usage and memory, both pointer usage and dynamic memory.
	in bonus part, we will introduce ourselves to linked lists usage
```
> [!NOTE]
> Because of 42 School norm requirements:
> * Each function can't have more than 25 lines of code.
> * All variables must be declared and aligned at the top of each function.
> * Project should be created just with allowed functions.
<br>

About
This project is a C library of useful functions that are allowed to be used in future School 42 cursus projects. With access to this library, the coding proccess in incoming projects will be more effective. The aim of rewrite this functions is to get a better understanding of them, and get a whide range of utilities for the next projects. You can find more information in the subject. As it's specified in the subjet, all the archives are in the same folder.

The code in this repository follows the rules of the Norminette.

Index
Functions from <ctype.h> library
ft_isascii - Test a character to see if it's a 7-bit ASCII character.
ft_isalpha - Test a character to see if it's alphabetic.
ft_isdigit - Test a character to see if it's a decimal digit.
ft_isalnum - Test a character to see if it's alphanumeric.
ft_isprint - Test a character to see if it's any printable character, including a space.
ft_tolower - Convert a character to lowercase.
ft_toupper - Convert a character to uppercase.
Functions from <stdlib.h> library
ft_atoi - Convert ASCII string to integer.
ft_calloc - Allocate space for an array and initializes it to 0. This function and malloc return a void pointer, that had no associated data type with it. A void pointer can hold address of any type and can be typecasted to any type.
Functions from <strings.h> library
ft_bzero - Set the first part of an object to null bytes (filling it with zeroes).
ft_memset - Set memory to a given value.
ft_memchr - Find the first occurrence of a character in a buffer (locate byte in byte string).
ft_memcmp - Compare the bytes in two buffers.
ft_memmove - Copy bytes from one buffer to another, handling overlapping memory correctly.
ft_memcpy - Copy bytes from one buffer to another.
Functions from <string.h> library
ft_strlen - Get the length of a string.
ft_strchr - Find the first occurrence of a character in a string.
ft_strrchr - Find the last occurrence of a character in a string.
ft_strnstr - Locate a substring in a string.
ft_strncmp - Compare two strings, up to a given length.
ft_strdup - Create a duplicate of a string, using malloc.
ft_strlcpy - Size-bounded string copy.
ft_strlcat - Size-bounded string concatenation.
Non-standard functions
ft_itoa - Convert integer to ASCII string.
ft_substr - Get a substring from string.
ft_strtrim - Trim beginning and end of string with the specified substring.
ft_strjoin - Concatenate two strings into a new string, using calloc.
ft_split - Split string, with specified character as delimiter, into an array of strings.
ft_strmapi - Create new string from a string modified with a specified function.
ft_striteri - Modify a string with a given function.
ft_putchar_fd - Output a character to given file.
ft_putstr_fd - Output string to given file.
ft_putendl_fd - Output string to given file with newline.
ft_putnbr_fd - Output integer to given file.
Linked list functions (bonus)
ft_lstnew - Create new list.
ft_lstsize - Count elements of a list.
ft_lstlast - Find last element of list.
ft_lstadd_back - Add new element at end of list.
ft_lstadd_front - Add new element at beginning of list.
ft_lstdelone - Delete element from list.
ft_lstclear - Delete sequence of elements of list from a starting point.
ft_lstiter - Apply function to content of all list's elements.
ft_lstmap - Apply function to content of all list's elements into new list.
Requirements
The library is written in C language and needs the gcc compiler, with <stdlib.h> and <unistd.h> standard libraries to run.

Instructions
1. Compiling the library
To compile the library, go to its path and run:

For basic functions:

$ make
For bonus functions:

$ make bonus
2. Cleaning all binary (.o) and executable files (.a)
To delete all files generated with make, go to the path and run:

$ make fclean
3. Using it in your code
To use the library functions in your code, simply include this header:

#include "libft.h"
