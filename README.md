<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/byaliego/42-project-badges/main/badges/libftm.png" width="150" />
<br>Libft</h1>
<h3>◦ Your very first own library</h3>

<p align="center">
<img src="https://img.shields.io/badge/Barcelona-100000?style=flat-square&logo=42&logoColor=white&labelColor=000000&color=000000" alt="42 Barcelona" />
</p>
<img src="https://img.shields.io/github/actions/workflow/status/San-tito/Libft/c.yml?style=flat-square" alt="GitHub%20Actions" />
<img src="https://img.shields.io/github/languages/code-size/San-tito/Libft?style=flat-square" alt="GitHub code size" />
<img src="https://img.shields.io/github/languages/top/San-tito/Libft?style=flat-square" alt="GitHub top language" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Use Libft](#-use-Libft)
    - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---

## 📍 Overview

The `Libft` project involves creating a C library containing a wide range of general-purpose functions to support your programs. These functions emulate the behavior of standard C library functions but are prefixed with "ft_".

---

## 📦 Features

**Libc Functions**: Reimplementation of standard C library functions with names prefixed by "ft_".
     `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`,
     `ft_strlen`, `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, 
     `ft_strlcpy`, `ft_strlcat`, `ft_toupper`, `ft_tolower`, `ft_strchr`, 
     `ft_strrchr`, `ft_strncmp`, `ft_memchr`, `ft_memcmp`, `ft_strnstr`, `ft_atoi`

**Additional Functions**: Extended functionality for string manipulation.
     `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_itoa`,
     `ft_strmapi`, `ft_striteri`, `ft_putchar_fd`, `ft_putstr_fd`,
     `ft_putendl_fd`, `ft_putnbr_fd`

---


## 📂 Repository Structure

```sh
└── Libft/
    ├── Makefile
    ├── ft_atoi.c
    ├── ft_bzero.c
    ├── ft_calloc.c
    ├── ft_isalnum.c
    ├── ft_isalpha.c
    ├── ft_isascii.c
    ├── ft_isdigit.c
    ├── ft_isprint.c
    ├── ft_itoa.c
    ├── ft_memchr.c
    ├── ft_memcmp.c
    ├── ft_memcpy.c
    ├── ft_memmove.c
    ├── ft_memset.c
    ├── ft_putchar_fd.c
    ├── ft_putendl_fd.c
    ├── ft_putnbr_fd.c
    ├── ft_putstr_fd.c
    ├── ft_split.c
    ├── ft_strchr.c
    ├── ft_strdup.c
    ├── ft_striteri.c
    ├── ft_strjoin.c
    ├── ft_strlcat.c
    ├── ft_strlcpy.c
    ├── ft_strlen.c
    ├── ft_strmapi.c
    ├── ft_strncmp.c
    ├── ft_strnstr.c
    ├── ft_strrchr.c
    ├── ft_strtrim.c
    ├── ft_substr.c
    ├── ft_tolower.c
    ├── ft_toupper.c
    └── libft.h

```

---


## ⚙️ Modules

<details closed><summary>Root</summary>

| File                                                                                           | Summary       |
| ---                                                                                            | ---           |
| [libft.h](https://github.com/zazaWiz4rd/libft/blob/main/libft.h)                                 | Header file with function prototypes |
| [Makefile](https://github.com/zazaWiz4rd/libft/blob/main/Makefile)                               | Makefile for compiling the library |

</details>


<details closed><summary>Libc functions</summary>

| File                                                                                           | Summary       |
| ---                                                                                            | ---           |
| [ft_toupper.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_toupper)                       | Convert character to uppercase |
| [ft_tolower.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_tolower)                       | Convert character to uppercase |
| [ft_strrchr.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strrchr)                       | Locate character in string from the end |
| [ft_strnstr.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strnstr)                       | Locate substring in string |
| [ft_strncmp.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strncmp)                       | Compare two strings up to a specified number of characters |
| [ft_strlen.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strlen)                         | Calculate the length of a string |
| [ft_strlcpy.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strlcpy)                       | Copy a string to a specified size |
| [ft_strlcat.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strlcat)                       | Concatenate strings with a specified size |
| [ft_strdup.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strdup)                         | Duplicate a string with malloc |
| [ft_strchr.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strchr)                         | Locate character in string |
| [ft_memset.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_memset)                         | Fill memory with a constant byte |
| [ft_memmove.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_memmove)                       | Copy memory area |
| [ft_memcpy.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_memcpy)                         | Copy memory area |
| [ft_memcmp.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_memcmp)                         | Compare memory areas |
| [ft_memchr.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_memchr)                         | Locate byte in byte string |
| [ft_isprint.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_isprint)                       | Check if a character is printable |
| [ft_isdigit.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_isdigit)                       | Check if a character is a digit |
| [ft_isascii.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_isascii)                       | Check if a character is an ASCII character |
| [ft_isalpha.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_isalpha)                       | Check if a character is an alphabet character |
| [ft_isalnum.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_isalnum)                       | Check if a character is alphanumeric |
| [ft_calloc.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_calloc)                         | Allocate and zero-initialize array |
| [ft_bzero.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_bzero)                           | Set a byte string to zero |
| [ft_atoi.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_atoi)                             | Convert a string to an integer |

</details>

<details closed><summary>Additional functions</summary>

| File                                                                                           | Summary       |
| ---                                                                                            | ---           |
#| [ft_substr.c](https://github.com/San-tito/Libft/blob/main/ft_substr.c)                         | Extract substring from string |
| [ft_strjoin.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strjoin)                       | Concatenate two strings |
| [ft_strtrim.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strtrim)                       | Trim leading and trailing a character from a string|
| [ft_split.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_split)                           | Split a string into an array of substrings |
| [ft_itoa.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_itoa)                             | Convert an integer to a string |
| [ft_strmapi.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_strmapi)                       | Apply a function to each character of a string |
| [ft_striteri.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_striteri)                     | Apply a function to each character of a string with its index |
| [ft_putstr_fd.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_putstr_fd)                   | Output a string to a file descriptor |
| [ft_putnbr_fd.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_putnbr_fd)                   | Output an integer to a file descriptor |
| [ft_putendl_fd.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_putendl_fd)                 | Output a string to a file descriptor, followed by a newline |
| [ft_putchar_fd.c](https://github.com/zazaWiz4rd/libft/blob/main/ft_putchar_fd)                 | Output a character to a file descriptor |

</details>

<details closed>

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone the Libft repository:
```sh
git clone https://github.com/San-tito/Libft
```

2. Change to the project directory:
```sh
cd Libft
```

3. Compile the dependencies:
```sh
make
```

### 🤖 Use Libft
Once the library is successfully compiled, you can use it in your projects. Link the `libft.a` file to your program, and include the `libft.h` header in your source files.
To compile your program with Libft, use:
```sh
gcc -o my_program my_program.c -L . -lft
```

### 🧪 Tests
```sh
/* Not implemented */
```

---


## 🛣 Roadmap

> - [X] `ℹ️  Implement linked list functions.`
> - [ ] `ℹ️  Continuous integration for automated testing.`
> - [ ] `ℹ️  Explore opportunities for optimization.`


---

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/San-tito/Libft/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/San-tito/Libft/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/San-tito/Libft/issues)**: Submit bugs found or log feature requests for SAN-TITO.

---

## 📄 License


This project is protected under the [UNLICENSE](https://choosealicense.com/licenses/unlicense) License. For more details, refer to the [LICENSE](LICENSE) file.

---

## 👏 Acknowledgments

- [Master Memory Management](https://medium.com/p/b86fedd39b96)
- [Libft - C Standard Library Rewrite](https://www.asidesigned.com/project-libft.html)
- [libftTester](https://github.com/Tripouille/libftTester)

[**Return**](#Top)

---
