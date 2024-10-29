#include <stdio.h>
int cp(int n);
int main(){
    int n, flag;
    printf("\n Enter the number:");
    scanf("%d", &n);
    flag=cp(n);
    if(flag==1)
    {
        printf("\n not prime");
    }
    else {
        printf("\n Prime");
    }
    return 0;
}
int cp(int n)
{
    if((n==0)||(n==1))
    {
        return 1;
    }
    int i;
    for(i=2;i<+n/2;i++)
    {
        if(n%i==0)
        {
            return 1;
        }
    }
    return 0;
}
