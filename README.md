# C++
#include <stdlib.h>
#include <stdio.h>


int main()
{
float height, weight, BMI;

printf("Enter your height (in meters): ");
scanf("%f", & height);

printf("Enter your weight (in kilograms): ");
scanf("%f", & weight);

BMI = weight/(height*height);

printf("Your body mass index is: ", BMI);

if (BMI<20)
printf("Danger, you are underweight");
else
if (20<BMI&&BMI<=25)
printf("Congratulations, you are at your weight");
else
if (25<BMI&&BMI<30)
printf("You are overweight");
else
if (30<BMI&&BMI<35)
printf("you are obese");
else
if (35<=BMI)
printf("You are morbidly obese");


return 0;

}
