#include <stdio.h>
#include<conio.h>
void main()
{
	int n,b,g,i,sum=0;
	printf("enter the series");
	scanf("%d",&n);
	printf("enter the difference and first term");
	scanf("%d%d",&b,&g);
	for(i=0;i<n;i++)
	{
		sum=sum+g;
		f=g+b;
	}
printf("sum is:%d",sum);
getch();
}
