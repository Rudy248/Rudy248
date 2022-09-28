#include<stdio.h>
#include<math.h>
float main()
{
	float a,b,c,d;
	printf("Choose the operator you want to select: \n");
	printf("1.Addition\n2.Subtraction\n3.Multiplication\n4.Division\n5.Exponential\n6.Square root\n");
	printf("Your choice is: ");
	scanf("%f",&d);
	if(d==1){
        printf("Enter the 1st number: ");
    	scanf("%f",&a);
    	printf("Enter the 2nd number: ");
    	scanf("%f",&b);
		c=a+b;
		printf("Your sum is: %0.02f",c);}
	else if(d==2){
        printf("Enter the 1st number: ");
    	scanf("%f",&a);
    	printf("Enter the 2nd number: ");
    	scanf("%f",&b);
		c=a-b;
		printf("Your difference is: %0.02f",c);}
	else if(d==3){
        printf("Enter the 1st number: ");
    	scanf("%f",&a);
    	printf("Enter the 2nd number: ");
    	scanf("%f",&b);
		c=a*b;
		printf("Your product is: %0.02f",c);}
	else if(d==4){
        printf("Enter the 1st number: ");
    	scanf("%f",&a);
    	printf("Enter the 2nd number: ");
    	scanf("%f",&b);
		c=a/b;
		printf("Your quotient is: %0.02f",c);}
	else if(d==5){
	    printf("Enter the number: ");
	    scanf("%f",&a);
	    printf("Enter the power: ");
	    scanf("%f",&b);
	    c=pow(a,b);
	    printf("Your answer is %0.02f",c);
	}
	else if(d==6){
	    printf("Enter the number you want to find square root of: ");
	    scanf("%f",&a);
	    c=sqrt(a);
	    printf("The square root is: %0.02f",c);
	}
	else{
		printf("Wrong option entered");}
	return 0;
}
