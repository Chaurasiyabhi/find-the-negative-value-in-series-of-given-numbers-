# find-the-negative-value-in-series-of-given-numbers-
#include<stdio.h>
#include<conio.h>
void main()
{
  int num,i,user,count=0;
  clrscr();
  printf("Enter No. of Number:");
  scanf("%d",&num);
  printf("Enter Numbers :");
  for(i=0;i<num;i++)
  {
    scanf("%d",&user);
    if(user<0)
    {
      count++;
    }
  }
  printf("Number With Negative Values = %d",count);
  getch();
}
