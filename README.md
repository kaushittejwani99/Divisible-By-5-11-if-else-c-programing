# Divisible-By-5-11-if-else-c-programing
This Program checks a given no is Divisible by 5 & 11 or not, using if-else.
#include<stdio.h>
#include<conio.h>
int main()
{
  int num;
  printf("this program Create to check the given no is Divisible by 5 & 11 or not.\n");
  printf("----Enter your no-----:-\n");
  scanf("%d",&num);
  if(num%5==0&&num%11==0)
     printf(" %d is divisible by 5 & 11.\n",num);
  else
     printf("%d is not divisible by 5 & 11.\n",num);
  printf("Checking successfully");
  getch();
  return 0;
}
