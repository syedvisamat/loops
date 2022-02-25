# loops
/to find the sum of this series upto to n terms {1+2+4+7+16......}
#include<stdio.h>
/*int main(){
int i,sum=0,terms=1,n;
printf("enter the number of terms:\n");
scanf("%d",&n);
for ( i = 1; i <=n; i++)
{
    sum=sum+terms;
    terms=terms+i;
}
printf("the sum of series upto %d terms is %d\n",n,sum);
return 0;
}
int main()//program to generate fibonacci series {1,1,2,3,5,8}
{long x,y,z;
int i,n;
x=0;y=1;
printf("enter the number of terms:\n");
scanf("%d",&n);
printf("%ld",y);
for ( i = 1; i <n; i++)
{
    z=x+y;
    printf("%ld",z);
    x=y;
    y=z;
}printf("\n");
return 0;
}
int main()//program to print sum for digits 
{int i,n,sum=0,r;
printf("enter the number:\n");
scanf("%d",&n);
for ( ; n>0 ;n=n/10)
{
    r=n%10;
    sum=sum+r;
    
}
printf("%d",sum);
return 0;
}
#include<math.h>
int main()//program to find number is prime or not
{int n,i;
printf("enter the number:\n");
scanf("%d",&n);
for ( i = 2; i <=sqrt(n); i++)
{
    if (n%i==0)
    {
        break;}
    }
    if (i>sqrt(n))
    {
        printf("%d is prime\n",n);
    }else
    printf("%d number is not prime\n",n);
    return 0;
}*/
int main()//to find sum and average of 10 positive numbers
{int sum=0,n,i=1;
float avg;
printf("enter numbers\n");
while (i<=10)
{printf("enter the numbers :\n");
scanf("%d",&n);
if (n<0)
{
printf("enter only positive numbers:\n");
continue;
}
sum=sum+n;
i++;
}avg=sum/10.00;
printf("%d\n",sum);
printf("%f\n",avg);
return 0;
}


#include <stdio.h> //print numbers from 1 tp 10 using while loop//
/*int main()
{int i=1;

while (i<=10)
{
   printf("%d",i);
   i=i+1;
}
//printf("\n");
return 0;
}
int main()//to print numbers in reverse order with a difference of 2//
{int j;
j=18;
while(j>=0)
{printf("%d\n",j);
j=j-2;
}
printf("\n");
return 0;
}
int main() // to print sum of digits of any number
{
    int i, rem, sum = 0;
    printf("enter the number:");
    scanf("%d", &i);
    while (i > 0)
    {
        rem = i % 10;
        sum =sum+ rem;
        i /= 10;
    }
    printf("sum of digits is %d", sum);
    return 0;
}
int main()//to find the product of the digits of number//
{int i,product=1,rem;
printf("enter the number:");
scanf("%d",&i);
while(i>0)
{rem=i%10;
product=product*rem;
i=i/10;}
printf("the product is %d",product);
return 0;
}
int main()//to find factorial of an number
{ int i,fact=1;
printf("enter any number:");
scanf("%d",&i);
while(i>0)
{fact=fact*i;
i--;
}printf("the factorial is %d",fact);
return 0;
}
#include<math.h>
int main()//to convert binary into decimal number
{int i,rem,num=0,j=0;
printf("enter the binary number:\n");
scanf("%d",&i);
while(i>0)
{rem=i%10;
num = num+(rem*pow(2,j));
i=i/10;
j++;
}
printf("the answer in decimal is %d",num);
return 0;
}*/
int main()
{int i=2;

do
{
if(i==5)
continue;
printf("%d",i);
i++;
} while (i<8);
printf("%d",i);
int n;
for ( n = 2; n < 8; n++)
{
    if(n==5)
    continue;
    printf("number =%d\n",n);
}
printf("out of loop\n");
/*int i=2;
do
{
if(i==5)
continue;
printf("%d",i);
i++;
} while (i<8);
printf("%d",i);*/
return 0;






}
#include <stdio.h> //print numbers from 1 tp 10 using while loop//
/*int main()
{int i=1;

while (i<=10)
{
   printf("%d",i);
   i=i+1;
}
//printf("\n");
return 0;
}
int main()//to print numbers in reverse order with a difference of 2//
{int j;
j=18;
while(j>=0)
{printf("%d\n",j);
j=j-2;
}
printf("\n");
return 0;
}
int main() // to print sum of digits of any number
{
    int i, rem, sum = 0;
    printf("enter the number:");
    scanf("%d", &i);
    while (i > 0)
    {
        rem = i % 10;
        sum =sum+ rem;
        i /= 10;
    }
    printf("sum of digits is %d", sum);
    return 0;
}
int main()//to find the product of the digits of number//
{int i,product=1,rem;
printf("enter the number:");
scanf("%d",&i);
while(i>0)
{rem=i%10;
product=product*rem;
i=i/10;}
printf("the product is %d",product);
return 0;
}
int main()//to find factorial of an number
{ int i,fact=1;
printf("enter any number:");
scanf("%d",&i);
while(i>0)
{fact=fact*i;
i--;
}printf("the factorial is %d",fact);
return 0;
}
#include<math.h>
int main()//to convert binary into decimal number
{int i,rem,num=0,j=0;
printf("enter the binary number:\n");
scanf("%d",&i);
while(i>0)
{rem=i%10;
num = num+(rem*pow(2,j));
i=i/10;
j++;
}
printf("the answer in decimal is %d",num);
return 0;
}*/
int main()
{int i=2;

do
{
if(i==5)
continue;
printf("%d",i);
i++;
} while (i<8);
printf("%d",i);
int n;
for ( n = 2; n < 8; n++)
{
    if(n==5)
    continue;
    printf("number =%d\n",n);
}
printf("out of loop\n");
/*int i=2;
do
{
if(i==5)
continue;
printf("%d",i);
i++;
} while (i<8);
printf("%d",i);*/
return 0;






}
