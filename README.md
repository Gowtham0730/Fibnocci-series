# Fibnocci-series
#include <stdio.h>

int printfib(int n)
{
 if(n==0 || n==1){
    return n;
 }
 else{
     return printfib(n-1)+printfib(n-2);
 }
     
 }



int main()
{
  int n;
   printf("enter n value\n");
   scanf("%d",&n);
   for(int i=0;i<=n;i++)
   {
       int res = printfib(i);
       printf("%d \n",res);
   }
  
  

    return 0;
}
