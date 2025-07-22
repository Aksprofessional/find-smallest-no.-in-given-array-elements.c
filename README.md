# find-smallest-no.-in-given-array-elements.c
// C program to find smallest no. in given array elements.
// C program to find smallest no. in given array elements
#include <stdio.h>

int main() {
    int s,l,i;

    printf("Enter the size of the array: ");
    scanf("%d", &s);

    int a[s]; 
    printf("Enter elements:\n");
    
    for (int i=0;i<s;i++)
        scanf("%d", &a[i]);
        
        s=a[0];
    for (int i = 1; i < s; i++)
        if(s>a[i])
        s=a[i];
    printf("smallest no.=%d",s);
    return 0;
}
