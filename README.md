#include <stdio.h>

int main()
{
    int a,b;
    scanf("%d%d",&a,&b);
    int diff1=60-a;
    int diff2=60-b;
    if(diff1<diff2)
    {
        printf("nearest is a %d",diff1);
    }
    else if(diff2<diff1)     
    { 
        printf("nearest is b %d",diff2);
        }
        else
        {
            printf("0");
    }
    }
