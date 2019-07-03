# C_190703-2-
C_Language_Class


첫 번째

#include <stdio.h>

int main()
{
	int i, j, p;

	for (i = 0; i <= 10; i++)
	{
		p = 1;
		for (j = 1; j <= i; j++)
			p *= j;
		printf("%2d! = %d\n", i, p);
	}
}


// 1~10 의 팩토리얼 값 구하기. 이중 for



두 번째

#include <stdio.h>

int main()
{
	int i, j, p;

	p = 1;
	for (i = 1; i <= 10; i++)
	{
		p = p * i;
		printf("%2d! = %d\n", i, p);
	}
}
