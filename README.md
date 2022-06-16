# CLAP4
Write a program in C, that asks from user to enter marks obtained in 5 subjects (out of 100) and find the percentage marks of student. The answer to this question is given below: To calculate percentage marks of a student in C programming, you have to ask from user to enter marks obtained in some number of subjects (5 subjects here, i.e. Physics, Chemistry, Math, CS, and English). Place summation of 5 marks in a variable say sum and place sum/5 in a variable say avg. Simply print average as the result on output]

#include <stdio.h>
int main() {
    int Math,Physics, Chemistry, CS,English,sum;
    float avg;
    printf("Math=");
    scanf("%d",&Math);
    printf("Physics=");
    scanf("%d",&Physics);
    printf("Chemistry=");
    scanf("%d",&Chemistry);
    printf("CS=");
    scanf("%d",&CS);
    printf("English=");
    scanf("%d",&English);
    sum=Math+Physics+Chemistry+CS+English;
    avg=sum/5.0;
    printf("Average is %f",avg);
    return 0;
}
  
