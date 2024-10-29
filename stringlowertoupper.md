#include <stdio.h>
#include <string.h>
#include <conio.h>
int main()
{
    char str[100], us[100];
    int i=0,j=0;
    printf("Enter the string:");
    fgets(str, 100, stdin);
    for(i=0;str[i]!='\0';i++)
    {
        if(str[i]>='A' && str[i]<='Z')
        {
            str[i]=str[i]+32;
        }
    }
    printf("\n The converted string is:");
    printf("%s", str);
    return 0;
}
