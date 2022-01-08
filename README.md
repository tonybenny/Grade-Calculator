# Grade-Calculator
Calculate grades of a student for entered marks

#include<stdio.h>
main()
{
float mark;
printf("Enter your marks:\n");
scanf("%g",&mark);
   {

if(mark>=85 && mark<=100)
{
printf("You got Grade A");
}
else if(mark>=74 && mark<=84)
{
printf("You got Grade B");
}
else if(mark>=55 && mark<=69)
{
printf("You got Grade C");
}
else if(mark>=40 && mark<=54)
    {
    printf("You got Grade D");
    }
else if(mark>100)    
{
printf("Invalid Entry");
}
else
{
printf ("You got Grade D");
}
}
return 0;
}
