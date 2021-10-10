### Exercise 2.10
In the `dweight.c` program (Tutorial 2.4), which spaces are essential?

### Solution
Here is the `dweight.c` program:

```c
#include <stdio.h>

int main(void)
{
	int height, length, width, volume, weight;

	height =  8;
	length = 12;
	 width = 10;
	volume = height * length * width;
	weight = (volume + 165) / 166;

	printf("Dimensions: %dx%dx%d\n", length, width, height);
	printf("Volume (cubic inches): %d\n", volume);
	printf("Dimensional weight (pounds): %d\n", weight);

	return 0;
}
```

### Solutions
(1) Betwen ‘#include’ and ‘<stdio>’ .
(2) Betwen return and 0 .
(3) Breakline betwen ‘#include<sdio>’ and ‘int main()’ .