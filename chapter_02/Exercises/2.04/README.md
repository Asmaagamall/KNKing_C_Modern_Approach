### Exercise 2.4
Write a program that declares several `int` and `float` variables--without
initializing them--and then prints their values. Is there any pattern to the
values? (Usually there isn't.)

### Solution

#### 2.4.c
```c
#include <stdio.h>

int main(void)
{
	int a, b, c;
	float f, d, e;
	
	printf("%d  %d  %d\n",a,b,c);
	printf("%f  %f  %f\n",f,d,e);
	return 0;
}
```
Output is:
```c
-1877692320  22037  -916085392
0.000000  0.000000  0.000000
```
Will produce some warnings:
```c
2_4.c:8:24: error: variable 'a' is uninitialized when used here [-Werror,-Wuninitialized]
        printf("%d  %d  %d\n",a,b,c);
                              ^
2.4.c:5:11: note: initialize the variable 'a' to silence this warning
     int a, b, c;
          ^
           = 0
```
