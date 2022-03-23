# Write-a-C-program-that-ask-the-user-to-enter-a-year-and-program-shows-that-year-is-leap-year-or-not
Write a C program that ask the user to enter a year and program shows that year is leap-year or not.


#include<stdio.h>
int main()
{
    int year;
    printf("Enter a year: ");
    scanf("%d",&year);

    if(year%400==0)
        printf("YES!! leap year.");

    else if(year%4==0 && year%100!=0)
        printf("YES!! leap year");

    else
        printf("NO!! not leap year.");

    return 0;
}
