#include<stdio.h>
main( )
{
      float  a[20];  int  sum=0,   i  ,  n; 
      
      printf("Insert number of subjects");
      scanf("%d", &n);
      
      for (i=1 ;  i<=n ;  i++)
      {
            printf("Enter the GPA of course  %d:" , i);
            scanf("%f" , &a[i]);
            
      }
      for  (i=1; i<=n; i++)
      {
            sum =    sum  +   a[i];
            
       }
      printf("\nAverage Cgpa is:%.2f",sum/( float)n);
}
