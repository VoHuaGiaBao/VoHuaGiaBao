#include <stdio.h>
int main()
{
    int n;
    printf("Hay nhap so: ");          *     *
    scanf("%d",&n);
    printf("*");                      *     *
    for(int i=0; i<n-2; i++)
    {
        printf(" ");
    } printf("*\n");
    for(int j=0; j<n-2; j++)
    {
        printf(" ");
    } printf("\n");
    printf("*");
    for(int i=0; i<n-2; i++)
    {
        printf(" ");
    } printf("*\n");
    
    
    return 0;
}
