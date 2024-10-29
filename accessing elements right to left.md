#include <stdio.h>
#include <string.h>
int main()
{
    char str[100], sstr[100];
    int i=0,n,j=0;
    printf("enter the string:");
    scanf("%s", str);
    printf("enter the value:");
    scanf("%d", &n);
    j=strlen(str)-n;
    while(str[j]!='\0')
    {
        sstr[i]=str[j];
        i++;j++;
    }
    sstr[i]='\0';
    printf("\n THE SUBSTRING IS:");
    puts(sstr);
    return 0;
}
