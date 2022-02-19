#Struct

```
#include <stdio.h>
#include <stdlib.h>

struct Student{
    double score;
    char grade;
};



int main(){
  
    struct Student std1;
    std1.score = 89;
    std1.grade = 'A';

    struct Student std2;
    std2.score = 70;
    std2.grade = 'B';

    printf("student 1 score is %.2f grade is %c\n",std1.score,std1.grade);
    printf("student 2 score is %.2f grade is %c\n",std2.score,std2.grade);


    return 0;
}


```
