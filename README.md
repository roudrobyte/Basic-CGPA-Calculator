# Basic-CGPA-Calculator
A very basic code for Basic CGPA calculator. I started C programming for two weeks. So it's a beginner level project.

#include<stdio.h>

int main()
{
    
    printf("Welcome to Roudro's GRS\n");
    
    float r;
    printf("Enter your numerical result\n");
    scanf("%f",&r);
    
    if(r<=100 && r>=97)
    {
        printf("Congratulations you got a EXCEPTIONAL result.\nYour CGPA is: 4.00 \n Letter Grade: A+");
        
    }
    else if(r<=96 && r>=91)
    {
        printf("Congratulations you got a EXCELLENT result.\nYour CGPA is: 4.00 \n Letter Grade: A");
    }
    else if(r<=90 && r>=85)
    {
        printf("Congratulations you got a EXCELLENT result.\nYour CGPA is: 3.7 \n Letter Grade: A-");
    }
    
    else if(r<=84 && r>=80)
    {
        printf("Congratulations you got a EXCELLENT result.\nYour CGPA is: 3.3 \n Letter Grade: B+");
    }
    
    else if(r<=79 && r>=75)
    {
  printf("Congratulations you got a GOOD result.\nYour CGPA is: 3.0 \n Letter Grade: B");
    }
    
    else if(r<=74 && r>=70)
    {
        printf("Congratulations you got a GOOD result.\nYour CGPA is: 2.7 \n Letter Grade: B-");
    }
    
    else if(r<=69 && r>=65)
    {
        printf("Congratulations you got a GOOD result.\nYour CGPA is: 2.3 \n Letter Grade: C+");
    }
    
    else if(r<=64 && r>=60)
    {
        printf("Congratulations you got a FAIR result.\nYour CGPA is: 2.0 \n Letter Grade: C");
    }
    
    else if(r<=59 && r>=57)
    {
        printf("Congratulations you got a FAIR result.\nYour CGPA is: 1.7 \n Letter Grade: C-");
    }
    
    else if(r<=56 && r>=55)
    {
        printf("Congratulations you got a FAIR result.\nYour CGPA is: 1.3 \n Letter Grade: D+");
    }
    
    else if(r<=54 && r>=52)
    {
        printf("Congratulations you got a POOR result.\nYour CGPA is: 1.0 \n Letter Grade: D");
    }
    else if(r<=51 && r>=50)
    {
        printf("Congratulations you got a POOR result.\nYour CGPA is: 2.0 \n Letter Grade: D-");
    }
    else if(r>=0 && r<=50)
    {
        printf("Sorry you're FAIL.\nYour CGPA is: 0.0 \n Letter Grade: F");
    }
    
    else{
        printf("Invaild RESULT. Try again.");
    }

    return 0;
}
