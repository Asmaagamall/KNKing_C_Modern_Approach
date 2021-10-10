### Exercise 2.01
Create and run Kernighan and Ritchie's famous "hello, world" program:
```c
#include <stdio.h>

int main(void)
{
    printf("hello, world\n");
}
```
Do you get a warning message from the compiler? If so, what's needed to make it
go away?

### Solution
Compiling using Online GDB and codeblocks IDE no warnings.
but in some compiler will produce warnings.We can avoid this warning by adding `return 0;` (see 2_01.c)