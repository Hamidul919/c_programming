# c_programming
first time try to programming and it is also my first upload
#include<conio.h>
#include<stdio.h>

int main(int argc, char const *argv[])
{
    int a,b;
    printf("Enter any number: ");
    scanf("%d",&a);

     printf("multiplication table of %d\n",a);

    for (b=1 ; b<=10; b=b+1)
    {
         
        printf("\n%d*%d=%d",a,b,(a*b));

      
    }
 getch ();
return 0;
}
