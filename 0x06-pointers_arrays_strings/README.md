# C - More pointers, arrays and strings

## Header File :file_folder:

* [main.h](main.h): Header file containing prototypes for all functions written in the project.

| File                 | Prototype                                                      |
| -------------------- | -------------------------------------------------------------- |
| `0-strcat.c`         | `char *_strcat(char *dest, char *src);`                        |
| `1-strncat.c`        | `char *_strncat(char *dest, char *src, int n); `               |
| `2-strncpy.c`        | `char *_strncpy(char *dest, char *src, int n); `               |
| `3-strcmp.c`         | `int _strcmp(char *s1, char *s2);`                             |
| `4-rev_array.c`      | `void reverse_array(int *a, int n);`                           |
| `5-string_toupper.c` | `char *string_toupper(char *);`                                |
| `6-cap_string.c`     | `char *cap_string(char *);`                                    |
| `7-leet.c`           | `char *leet(char *);`                                          |
| `100-rot13.c`        | `char *rot13(char *);`                                         |
| `101-print_number.c` | `void print_number(int n);`                                    |
| `102-magic.c`        |  No Prototype                                                  |
| `103-infinite_add.c` | `char *infinite_add(char *n1, char *n2, char *r, int size_r);` |
| `104-print_buffer.c` | `void print_buffer(char *b, int size);                         |

## Tasks :page_with_curl:

* **0. strcat**
  * [0-strcat.c](./0-strcat.c): C function appends the src string to the dest string, overwriting the terminating null byte (\0) at the end of dest, and then adds a terminating null byte.

* **1. strncat**
  * [1-strncat.c](./1-strncat.c): C function that is similar to the _strcat function, except that it will use at most n bytes from src and src does not need to be null-terminated if it contains n or more bytes.

* **2. strncpy**
  * [2-strncpy.c](./2-strncpy.c): C function that copies a string.

* **3. strcmp**
  * [3-strcmp.c](./3-strcmp.c): C function that compares two strings.

* **4.  I am a kind of paranoid in reverse. I suspect people of plotting to make me happy**
  * [4-rev_array.c](./4-rev_array.c): C function that  reverses the content of an array of integers.

* **5. Always look up**
  * [5-string_toupper.c](./5-string_toupper.c): C function that changes all lowercase letters of a string to uppercase.

* **6.  Expect the best. Prepare for the worst. Capitalize on what comes**
  * [6-cap_string.c](./6-cap_string.c): C function that capitalizes all words of a string.

* **7. Mozart composed his music not for the elite, but for everybody**
  * [7-leet.c](./7-leet.c): C function that  encodes a string into 1337.

* **8. rot13**
  * [100-rot13.c](./100-rot13.c): C function that encodes a string using rot13.
  
* **9. Numbers have life; they're not just symbols on paper**
  * [101-print_number.c](./101-print_number.c): C function that prints an integer.

* **10. A dream doesn't become reality through magic; it takes sweat, determination and hard work**
  * [102-magic.c](./102-magic.c): C function that prints a[2] = 98, followed by a new line.

* **11. It is the addition of strangeness to beauty that constitutes the romantic character in art**
  * [103-infinite_add.c](./103-infinite_add.c): C program that adds two numbers.
 
* **12. Noise is a buffer, more effective than cubicles or booth walls**
  * [104-print_buffer.c](./104-print_buffer.c): C program that  prints a buffer.
