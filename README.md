//divisible_by_5
#include<stdio.h>
int main()
{
int i;
printf("enter a number\n");
scanf("%d",&i);
if(i%5==0)
{
printf("the number is divisible by 5 : %d\n",i);
}
else
{
printf("not divisible by 5.\n");
}
return 0;
}
