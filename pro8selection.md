#Selection 1 if

```
#include <stdio.h>
#include <stdlib.h>

int main(){

    if(1 > 2){
        printf("true\n");
    }else{
        printf("flase\n");
    }

    if('a' < 'b'){
        printf("true\n");
    }else{
        printf("flase\n");
    }



    int shop = 0;  //shop close
    //int shop = 1;  //shop open

    if(shop != 0){
        printf("shopping\n");
    }

    if(shop == 0){
        printf("go home\n");
    }else{
        printf("shopping\n");
    }



    int score = 65;
    //int score = 40;
    //int score = 52;
    if(score < 50){
       printf("grade 0\n");
    }else if(score <= 60){
        printf("grade 1\n");
    }else{
        printf("grade 2\n");
    }


    


    return 0;
}


```

-operator
< , > , <= , >= ,!= , ==
&& , || , !
