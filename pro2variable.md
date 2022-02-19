#variable

```
#include <stdio.h>
#include <stdlib.h>

int main(){
    char grade = 'A';
    char name[]  = "Tony";

    int ageNow = 17;
    short ageDex = 10;
    long ageTho = 18;
    long long age2mr =  25;

    float gpa = 3.5;
    double gpb = 3.6;
    long double gpc = 3.2;

    int isWork;
    isWork = 0;

    printf("student name %s",name);
    printf("grade is %c",grade);
    printf("gpa is %f",gpa);







    return 0;
}


```
-variable names are case-sensitive
-letter,numbers
-variable have signed and unsigned
| format |             descript                  |
|-------:|:-------------------------------------:|
|   %c   |   character                           |
|   %d   |   interger number (base 10)           |
|   %e   |   exponential floating-point number   |
|   %f   |   floating-point number               |
|   %i   |   interger  (base 10)                 |
|   %o   |   octal number (base8)                |
|   %s   |   strings of characters               |
|   %u   |   unsigned decimal(interger) number   |
|   %x   |   hexadecimal number (base 16)        |
|   %%   |   percent sign                        |
