
#include<studio.h>
int main()
{
int n,num=156,sum=0,rem=0;
n=num;
while(num>0)
{
rem=num%10;
sum=sum+rem;
num=num/10;
}
if(n%sum==0)
printf("harshad number");
else
Printf("not  harshad number");
return 0;
}
