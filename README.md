#include<stdio.h>
#include<stdlib.h>
int main()
{
int X,P,sum=0;
scanf("%d%d",&X,&P);
P=100-P;
while(X>0)
{
sum=sum+X;
X=(P*X)/100;
}
printf("%d\n",sum);
return 0;
}
