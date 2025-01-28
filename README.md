# C-code-1
Border Pattern Plotter in C langauage

#include <stdio.h>

int main()
{
    int n;
    printf("Enter a number:");
    scanf("%d",&n);
    for(int i=0;i<=n;i++){
        for(int j=0;j<=n;j++){
            if( i==n||j==n||i==0||j==0){
                printf("* ");
            }
            else{
                printf("  ");
            }
        }
         printf("\n");
    }
    return 0;
}
