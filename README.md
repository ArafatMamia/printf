#### Function prototype
```
int _printf(const char *format, ...);
```
#### Implemented format specifiers

| Specifier type | Description |
| --- | --- |
| c | Single character |
| s | String of characters |
| d or i | Signed decimal integer |
| b | Unsigned binary |
| u | Unsigned decimal integer |
| o | Unsigned octal |

#### Compilation and testing

We compiled via:
```
$ gcc -Wall -Werror -Wextra -pedantic *.c
