# For-loop-in-fibonacci-series-in-C-program
#include <stdio.h>
void fib(int a, int b, int n);
int main() {
   int a,b,c,n;
   scanf("%d",&n);
   printf("%d %d",a,b);
   fib(a,b,n);
   return 0;}
   void fib(int a,int b,int n){
       int c;
       for(int i=2;i<n;i++){
           c=a+b;
           printf("%d",c);
           a=b;
           b=c;
           
       }
   }
