/*CODE EMPWROR*/

#include <stdio.h>


int main ()

{

     double num1;
     double num2;
     char op;


      printf("Enter a number : ");
      scanf("%lf", &num1);

     
     printf("Enter Operator : ");
     scanf("%c", &op);

     printf("Enter a number : ");

     scanf("%lf", &num2);


    if (op = '+') {
     printf("%lf", num1 + num2);


   } else   if (op = '-') {
     printf("%lf", num1 - num2);


    } else   if (op = '*') {
     printf("%lf", num1 * num2);

    } else   if (op = '/') {
     printf("%lf", num1 / num2);

    } else {
      printf("INVALID OPERATOR");


     return 0;


     }
