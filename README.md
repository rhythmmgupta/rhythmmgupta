#include<stdio.h>
int main ()
{
    int a=0,b=1,c;
    for (int i=1;i<=10;i++)
    {
        printf ("%d" ,a);
        a=b;
        b=c;
        c=a+b;
    }
    return 0;
}
