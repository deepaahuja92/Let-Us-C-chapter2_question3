/*# Let-Us-C-chapter2_question3
In this question we have to find the area of triangle*/
#include<stdio.h>
#include<math.h>
int main()
{
float a,b,c,s;
printf("Enter the first side of triangle:");
scanf("%f",&a);
printf("Enter the second side of triangle:");
scanf("%f",&b);
printf("Enter the second side of triangle:");
scanf("%f",&b);
s=(a+b+c)/2;
float areasquare=s*(s-a)*(s-b)*(s-c);
float area=sqrt(areasquare);
printf("Area of the triangle is: %f",area);
return 0;
}
