#Function

```
#include <stdio.h>
#include <stdlib.h>

void plus(int pnum1,int pnum2);
int minus(int mnum1,int mnum2);

int main(){
    plus(2,3);
    int x = 6;
    int y = 2;
    int ansMinus = minus(x,y);
    printf("%d - %d = %d",x,y,ansMinus);
    return 0;
}

void plus(int pnum1,int pnum2){
    printf("%d + %d = %d\n",pnum1,pnum2,pnum1+pnum2);
}

int minus(int mnum1,int mnum2){
    return mnum1-mnum2;
}


```
