#include<stdio.h>
#include<stdio.h>
int main(){
int n;
printf("Enter the no:");
scanf("%d",&n);
printf("the fact of no is %d" ,fact(n));
}
int fact(int n){
if(n==0||n==1)
return 1;
else
return n*fact(n-1);
}
