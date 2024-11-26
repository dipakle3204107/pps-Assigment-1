# pps-Assigment-1
#include<stdio.h>
int main()
{
int a;
a=10;
int *ptr;
ptr=&a;
printf("address of a is %X\n",a);
printf("value of a is %d\n",a);
printf("address of a is %X\n",ptr);
printf("value of a is %d\n",*ptr);
}
