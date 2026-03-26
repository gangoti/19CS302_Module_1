# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
Start. Declare the variables. Prompt the user to enter a value. Read the value using scanf. Calculate the number of years using the formula: End .
## Program:
```
#include <stdio.h> 
#include <math.h>
int main()
{
float p,n,r,si,ci; 
scanf("%f%f%f", &p,&n,&r);
si=((p*n*r)/100); 
ci=(p)*(pow((1+ r/100),n));
printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci);
return 0;
}
/*
Program to find number of years based on principle,rate & simple interest.
Developed by:GONGOTI SANDEEP YADAV
RegisterNumber:212222060067
*/
```

## Output:
<img width="828" height="318" alt="image" src="https://github.com/user-attachments/assets/ee8ad270-1bdf-44a4-8b3b-de6cf26dbd41" />



## Result:
Thus the program was executed and the output was verified successfully.
