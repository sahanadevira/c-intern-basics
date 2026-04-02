// SIMPLE CALCULATOR 
#include<stdio.h>

//FUNCTION DECLARATION 
float add(float,float);
float sub(float,float);
float mul(float,float);
float division(int,int);
int modulo(int,int);

int main(){
    int choice,a,b;
    float x,y;
    printf("\nSIMPLE CALCULATOR\n");
    printf("\n------MENU-----\n");
    printf("\n1. Addition");
    printf("\n2. Subtraction");
    printf("\n3. Multiplication");
    printf("\n4. Division");
    printf("\n5. Modulo");
    printf("\n6. Exit");
    do 
    {
        printf("\n\nEnter your choice number: ");
        scanf("%d",&choice);
        switch(choice)
        {
            case 1:
                printf("Enter x and y: ");
                scanf("%f%f",&x,&y);
                printf("x + y = %.3f",add(x,y));
                break;
            case 2:
                printf("Enter x and y: ");
                scanf("%f%f",&x,&y);
                printf("x - y = %.3f",sub(x,y));
                break;
            case 3:
                printf("Enter x and y: ");
                scanf("%f%f",&x,&y);
                printf("x * y = %.3f",mul(x,y));
                break;
            case 4:
                printf("Enter x and y: ");
                scanf("%d%d",&a,&b);
                printf("x / y = %d",division(a,b));
                break;
            case 5:
                printf("Enter x and y: ");
                scanf("%d%d",&a,&b);
                printf("x % y = %d",modulo(a,b));
                break;
            case 6:
                printf("\nExiting the calculator....");
                break;
            default:
                printf("\nInvalid choice! Please try again...");
            }
        }while(choice!=6);
        return 0;
    }
    //FUNCTION DEFINITIONS
    float add(float x,float y){
        return x+y;
    }
    float sub(float x,float y){
        return x-y;
    }
    float mul(float x,float y){
        return x*y;
    }
    float division(int x,int y){
        return x/y;
    }
     modulo(int x,int y){
        return x%y;
    }
