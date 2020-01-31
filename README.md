#include <stdio.h>

int main()
{
    int n,a[10],i,even=0,odd=0;
    float avg;
    printf("enter the number:");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    
    for(i=0;i<n;i++)
    {
        if(a[i]%2==0)
        even+=a[i];
        else
        odd+=a[i];
        
        
    }
    printf("even=%d",even);
    printf("odd=%d",odd);
        
    return 0;
}
output:
enter the number:4
2
6
7
5
even=8 odd=12
