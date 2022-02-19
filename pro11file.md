#File

```
#include <stdio.h>
#include <stdlib.h>

int main(){

    FILE *ffile = fopen("e:\\test.txt","w");
    fprintf(ffile,"student 1\nstudent 2\n");
    fclose(ffile);


//    FILE *ffile = fopen("e:\\test.txt","a");
//    fprintf(ffile,"student 3\nstudent 4\n");
//    fclose(ffile);


//    char line[255];
//    FILE *ffile = fopen("e:\\test.txt","r");
//    fgets(line,255,ffile);
//    printf("%s",line);
//    fgets(line,255,ffile);
//    printf("%s",line);
//    fclose(ffile);
    

    return 0;
}


```
