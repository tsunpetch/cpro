#Input Output

```
#include <stdio.h>
#include <stdlib.h>

int main(){

    char name[30];
    printf("Enter your name: ");
    fget(name,30,stdin);
    printf("You name is %s \n",name);

    int age;
    printf("Enter your age: ");
    scanf("%d",&age);
    printf("You are %d \n",age);

    char grade;
    printf("Enter your grade: ");
    scanf("%c",&grade);
    printf("You got an  %c \n",grade);

    double gpa;
    printf("Enter your gpa: ");
    scanf("%lf",&gpa);
    printf("You gpa is %f \n",gpa);


    return 0;
}


```
