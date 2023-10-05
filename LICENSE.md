#include<stdio.h>
#include<stdlib.h>
int main()
{
	int num,fact=1,ognum;
	system("clear");
	printf("Varsha Singh Parihar\n");
	printf("----------------------\n");
	printf("Enter the number:");
	scanf("%d",&num);
	ognum=num;
	do{
		fact=fact*num;
		num--;
		
	}
	while (num>0);
	printf("Factorial of %d = %d",ognum,fact);
	printf("\n\n");
	return 0;
	
	
	
}
