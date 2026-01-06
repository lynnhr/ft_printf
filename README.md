# ft_printf

*This project has been created as part of the 42 curriculum by <lhaydar>.*

## Description
`ft_printf` is a project that re-implements the standard C `printf` function.  
The goal of this project is to deepen understanding of:
- Variadic functions in C (`va_list`, `va_start`, `va_arg`, `va_end`)
- Format specifiers handling (`%d`, `%s`, `%x`, `%p`, etc.)
- Writing modular and efficient code in C  
This project also emphasizes careful memory management and robust error handling.

## Instructions
To compile and run the project:

```bash
# Clone the repository
git clone <repository_url>
cd ft_printf

# Compile the library and test files
gcc -Wall -Wextra -Werror -c *.c
ar rcs libftprintf.a *.o

# Run tests
gcc -o test main.c -L. -lftprintf
./test
```
## Resources
- **Documentation & References**
  - [C Standard Library `printf`](https://www.cplusplus.com/reference/cstdio/printf/)  
  - [42 ft_printf subject PDF](<subject_link>)  
  - StackOverflow: 



