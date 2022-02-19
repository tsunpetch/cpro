#pointer

```
#include <stdio.h>
#include <stdlib.h>

int main(){

    int residents1  = 2;
    int residents2  = 6;

    int *residents1Address = &residents1;
    int *residents2Address  = &residents2;


    printf("Residents  1 :  baan  address number %p house members %d",residents1Address,residents1);
    printf("Residents  2 : baan  address number %p house members %d",residents2Address,residents2);
    
    printf("postman sent mail to residents 2 at %p",residents2Address);


    return 0;
}


```

-value or member of baan
-address 

* Residents  1 :  baan number address ?
 house members 2
* Residents  2 : baan number address ?
 house members 6

postman
