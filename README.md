# homework //


#include <stdio.h>
#define MAX_NUM 100

int main ()
{
    int num = 2, i;

    while (num <= MAX_NUM) {
        i=2;

        while (i < num) {

            if ( num % i ==0) break;
            i++;
        }
        if (num == i) printf("%d", num  );
        num++

    }
    prinf("\n");
    return 0;
}
