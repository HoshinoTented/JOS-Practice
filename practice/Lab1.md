## Exercise 8

1. `inc/stdio.h`; cputchar, getchar, iscons; only cputchar is used in `printf.c`, it used for implementing putch(int, int \*).
2. scrolling one line up, and fill the last line with whitespace.
3.
  1. fmt points format string: "x %d, y %x, z %d"; According to [the documment](https://www.gnu.org/software/libc/manual/html_node/Argument-Macros.html), ap poitns to the first variable argument;
  2.
     * For `cons_putc`: 'x', ' ', '1', ',', ' ', 'y', ' ', '3', ',', ' ', 'z', ' ', '4', '\n' 
     * For `va_arg` (Before, After): (x, y), (y, z), (z, ?)
     * For `vcprintf`: vcprintf(fmt, ap) in `cprintf`
   
