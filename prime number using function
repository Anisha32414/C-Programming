#include<stdio.h>
#include<conio.h>
#include<stdbool.h>
void num_is_prime(int num)
{
    int i=2,temp=0;
    for(i=2;i<num;i++)
    {
        if(num%i==0)
        {
            printf("false - num is not prime");
            temp=1;
            break;   
        }
    }
    if(temp==0)
        printf(" True- num is prime");
}
int main()
{
    int num;
    printf("enter any number");
    scanf("%d",&num);
    num_is_prime(num);
    return 0;
}
