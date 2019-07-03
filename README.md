# C_190703-2-
C_Language_Class



#include <stdio.h>

int main()
{
	int i, j, p;

	for (i = 0; i <= 10; i++)
	{
		p = 1;
		for (j = 1; j <= i; j++)
			p *= j;
		printf("%d!=%d\n", i, p);
	}
}


// 1~10 의 팩토리얼 값 구하기. 이중 for
