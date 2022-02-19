#Selection 2 switch

```
#include <stdio.h>
#include <stdlib.h>

int main(){

    char grade = 'A';
    switch(grade){
        case 'A': printf("grade %c pass\n",grade);  break;
        case 'B': printf("grade %c pass\n",grade);  break;
        case 'C': printf("grade %c pass\n",grade);  break;
        case 'D': printf("grade %c pass\n",grade);  break;
        case 'F': printf("grade %c fail\n",grade);  break;
        defaule:  printf("Invalid grade\n");

    }

    char grade = 'B';
    switch(grade){
        case 'A' :
        case 'B' :
        case 'C' :
        case 'D' :
             printf("grade %c pass\n",grade);  break;
        case 'F': printf("grade %c fail\n",grade);  break;
        defaule:  printf("Invalid grade\n");

    }




    return 0;
}


```

-operator
< , > , <= , >= ,!= , ==
&& , || , !
