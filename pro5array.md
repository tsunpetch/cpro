#Array

```
#include <stdio.h>
#include <stdlib.h>

int main(){

    int scoreDB[] = {56,65,75,84,66};
    printf("scoreDb no.1 = %d\n",scoreDB[0]);
    printf("scoreDb no.4 = %d\n",scoreDB[3]);

    int scoreProg[3];
    scoreProg[0] = 77;
    scoreProg[1] = 57;
    scoreProg[2] = 76;
    printf("scoreProg no.1 = %d\n",scoreProg[0]);
    printf("scoreProg no.2 = %d\n",scoreProg[1]);
    
    
    float grade[2][3] = {{55,65,83},{1.5,2.5,4}};
    printf("score = %.2f grade = %.1f\n",grade[0][0],grade[1][0]);
    printf("score = %.2f grade = %.1f\n",grade[0][1],grade[1][1]);
    printf("score = %.2f grade = %.1f\n",grade[0][2],grade[1][2]);  
    
    
    return 0;
}


```

- index begin 0