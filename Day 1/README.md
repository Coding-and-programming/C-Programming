# Welcome to Day 1 of C Programming Language

### Let's Start with the Basics

C is a programming language developed by Dennis Ritchie in AT & T's Bell Laboratories.

### Now, let's take a look at simple C Program

```c
// Simple Hello World in C
#include <stdio.h>

int main()
{
  printf("Hello World!");
  return 0;
}
```

### Explining the sample C program

The first line is:

```c
#include <stdio.h>
```

It is used for including header files or the preprocessor directives in the program.

stdio.h is the standard input/output header files which provides function like

printf() => To print output
scanf() => To take input

The second line is the main function which executes at the beginning.

The curly braces {} shows the body of the main function.

Now,

```c
printf("Hello World");
```

prints **Hello World**

---------------

return 0 is required to return integer value 0 which means that the program executed successfully.

In **Programming** terms, 0 means **EXIT_SUCCESS** wheres 1 means **EXIT_FAILAURE**.
