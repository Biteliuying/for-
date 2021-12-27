# for-
for(int k=1;k&lt;=i;k++)
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int main()
{
	int n = 18;
	for (int i = 1;i <= n;i++)
	{
		for (int k = 1;k <= i;k++)
		{
			printf("*");
		}
		printf("\n");
	}
	printf("exit..");
	//if(n%2==0) //n为偶数，从小到大打印
	//	for (int i = 1;i <= n;i++)
	//	{
	//		printf("%d\n", i);
	//	}
	//else
	//	for (int i = n;i > 0;i--)//n为奇数，从大到小打印
	//	{
	//		printf("%d\n", i);
	/*	}*/
	return 0;
}
