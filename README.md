# addition-of-two-array-a-and-b
#include <stdio.h>

int main()
{
    int a[4]={12,34,56,23};
    int b[4]={02,45,23,15};
    int sum[4];
    int i;
    for(i=0;i<=4;i++)
    {
        sum[i]=a[i]+b[i];
    }
    for(i=0;i<=4;i++)
    {
        printf("\n sum of two array is \n%d",sum[i]);
    }
    return 0;
}
