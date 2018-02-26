#include<stdio.h>
#include <stdlib.h>
int main()
{
    char a[1000];
    int n,i;
    scanf("%s%d",a,&n);
    for(i=n;i<strlen(a);i++)
    {
    printf("%c",a[i]);
    }
    for(i=0;i<n;i++)
    {
    printf("%c",a[i]);
    }
}
