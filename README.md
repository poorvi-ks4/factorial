#include<stdio.h>
#include<stdlib.h>
int fact( int n)
{
if(n==0 || n==1)
return 1;
else
return n* fact(n-1);
}
int main()
{
int num;
printf("enter a postive number\n");
scanf("%d",&num);
printf("the factorial of the entred number is %d",fact(num));
}
