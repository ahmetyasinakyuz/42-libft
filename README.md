# libft - 42 School Project

A custom implementation of standard C library functions and additional utility functions.

## 📖 About

**libft** is the first project at 42 School. The goal is to re-implement several functions from the C standard library (`libc`) as well as additional utility functions that will be useful throughout the 42 curriculum. This project helps develop a deeper understanding of basic algorithms, data structures, and memory management in C.

## 🚀 Getting Started

### Prerequisites

- GCC or Clang compiler
- Make

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ahmetyasinakyuz/42-libft.git
cd 42-libft/libft
```

2. Compile the library:
```bash
make
```

This will create a `libft.a` static library file.

3. To compile with bonus functions:
```bash
make bonus
```

### Usage

Include the header in your C files:
```c
#include "libft.h"
```

Compile your program with the library:
```bash
gcc your_program.c -L. -lft -o your_program
```

Or compile with the library directly:
```bash
gcc your_program.c libft.a -o your_program
```

## 📚 Function List

### Part 1 - Libc Functions

#### Character Checks
- `ft_isalpha` - Check if character is alphabetic
- `ft_isdigit` - Check if character is a digit
- `ft_isalnum` - Check if character is alphanumeric
- `ft_isascii` - Check if character is ASCII
- `ft_isprint` - Check if character is printable

#### String Functions
- `ft_strlen` - Calculate string length
- `ft_strchr` - Locate character in string
- `ft_strrchr` - Locate character in string (from end)
- `ft_strncmp` - Compare strings up to n bytes
- `ft_strlcpy` - Copy string with size limit
- `ft_strlcat` - Concatenate strings with size limit
- `ft_strnstr` - Locate substring in string

#### Memory Functions
- `ft_memset` - Fill memory with constant byte
- `ft_bzero` - Zero a byte string
- `ft_memcpy` - Copy memory area
- `ft_memmove` - Copy memory area (handles overlap)
- `ft_memchr` - Scan memory for character
- `ft_memcmp` - Compare memory areas

#### Conversion Functions
- `ft_atoi` - Convert string to integer
- `ft_toupper` - Convert character to uppercase
- `ft_tolower` - Convert character to lowercase

#### Memory Allocation
- `ft_calloc` - Allocate and zero memory
- `ft_strdup` - Duplicate string

### Part 2 - Additional Functions

- `ft_substr` - Extract substring from string
- `ft_strjoin` - Concatenate two strings
- `ft_strtrim` - Trim characters from string
- `ft_split` - Split string by delimiter
- `ft_itoa` - Convert integer to string
- `ft_strmapi` - Apply function to each character
- `ft_striteri` - Apply function to each character with index
- `ft_putchar_fd` - Output character to file descriptor
- `ft_putstr_fd` - Output string to file descriptor
- `ft_putendl_fd` - Output string with newline to file descriptor
- `ft_putnbr_fd` - Output number to file descriptor

### Bonus - Linked List Functions

- `ft_lstnew` - Create new list element
- `ft_lstadd_front` - Add element to beginning of list
- `ft_lstsize` - Count elements in list
- `ft_lstlast` - Get last element of list
- `ft_lstadd_back` - Add element to end of list
- `ft_lstdelone` - Delete single element
- `ft_lstclear` - Delete and free list
- `ft_lstiter` - Iterate and apply function to list
- `ft_lstmap` - Create new list by applying function

## 🛠️ Makefile Commands

- `make` - Compile the library
- `make bonus` - Compile the library with bonus functions
- `make clean` - Remove object files
- `make fclean` - Remove object files and library
- `make re` - Recompile everything

## 📋 Project Structure

```
42-libft/
├── libft/
│   ├── *.c          # Source files
│   ├── libft.h      # Header file
│   └── Makefile     # Build configuration
└── README.md        # This file
```

## ⚙️ Compilation Flags

The library is compiled with the following flags:
- `-Wall` - Enable all warnings
- `-Wextra` - Enable extra warnings
- `-Werror` - Treat warnings as errors

## 👨‍💻 Author

**Ahmet Yasin Akyüz** - [ahmetyasinakyuz](https://github.com/ahmetyasinakyuz)

## 📝 License

This project is part of the 42 School curriculum.

## 🎓 42 School

This project is part of the common core curriculum at [42 School](https://www.42.fr/).

---

*Made with ☕ at 42 School*