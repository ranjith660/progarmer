# programmer
# python
#HTML
#cpp
#rust
#bash
#solidity
#Php
#sql


#include <stdio.h>
int main ()
{
  int i, j, n, sum = 0, a[100], c;
  printf ("Enter a values : ");
  scanf ("%d", &n);
  printf ("Enter the numbers : \n");
  for (i = 0; i < n; i++)
    {
      scanf ("%d", &a[i]);
      sum = sum + a[i];
    }
  printf ("Sum of numbers :  %d", sum);
  c=(sum/n);
  printf("\nAverage of numbers : %d", c);
  return 0;
}


