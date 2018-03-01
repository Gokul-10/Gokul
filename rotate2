#include<stdio.h>

int main()
{
   int number,rot,num,pos=0,j,arr[15],i=0,temp;
   scanf("%d %d",&number,&rot);
   num = number;
   
   while(num > 0)
   {
       arr[i] = num%10;
       num = num/10;
       i++;
   }
   
   pos= i;
   
   for(i=0 ; i<rot ; i++)
   {
       temp = arr[pos-1];
       for(j=pos-2 ; j>=0 ; j--)
       {
           arr[j+1] = arr[j];
       }
       arr[0] = temp;
   }

    for(i=pos-1 ; i>=0 ; i--)
    {
        printf("%d",arr[i]);
    }
}
