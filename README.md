#include<stdio.h>
int main(){
printf("25331A05E9\n");
    int a,b,choice;
    float result;
    printf("enter two numbers:");
    scanf("%d %d",&a,&b);
    printf("\n choose an operation:\n");
    printf("1. addditon(+)\n");
    printf("2. substration(-)\n");
    printf("3. multiplication(*)\n");
    printf("4. division(/)\n");
    printf("enter your choice:");
    scanf("%d",&choice);
    switch (choice){
        case 1:
        result=a+b;
        printf("result=%.2f",result);
        break;
        case 2:
        result=a-b;
        printf("result=%.2f",result);
        break;
        case 3:
        result=a*b;
        printf("result=%.2f",result);
        break;
        case 4:
        result=a/b;
        printf("result=%.2f",result);
        break;
        return 0;
    }
        
        
    
}
