# programme on "Do while loop " in C programming language
 programme on "Do while loop " in C programming language to understand how actually "Do while loop " work
#include<stdio.h>


int main()
{
    int num,index = 0;
    printf("Enter a number\n");
    scanf("%d",&num);

    do
    {
        printf("%d\n", index+1);
        index = index+1;
    } while (index<num);

    return 0;
    
    
}