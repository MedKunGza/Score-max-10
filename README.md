#include<stdio.h>

int main()
{   
    float x,y,z,all;
    printf("Input assignment = ");
    scanf("%f",&x);
    printf("Input midterm = ");
    scanf("%f",&y);
    printf("Input final = ");
    scanf("%f",&z);
    all = x*0.1+y*0.4+z*0.5;
    printf("Overall score = %.2f",all);
    return 0;
}
