#include <math.h>
#include <stdio.h>
#include <string.h>
#include <stdlib.h>
#include <assert.h>
#include <limits.h>
#include <stdbool.h>

int main(){
    int t; 
    scanf("%d",&t);
    for(int a0 = 0; a0 < t; a0++){
        int n; 
        scanf("%d",&n);
        long sum = 0;
        long n_5 = (n - 1) / 5;
        long n_3 = (n - 1) / 3;
        long n_15 = (n - 1) / 15;
        sum = sum + (n_3*(6 + (n_3 - 1) * 3)/2);
        sum = sum + (n_5*(10 + (n_5 - 1) * 5)/2);
        sum = sum - (n_15*(30 + (n_15 - 1) * 15)/2);
        printf("%ld\n", sum);
    }
    return 0;
}
