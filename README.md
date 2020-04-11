# switch-case
Developed by Gunjan Narkhede
#include<stdio.h>
int main()
{
	int n;
	printf("enter yoir choice");
	scanf("%d",&n);
    switch(n)
     {
	    case(1):
        {
	        printf("fooditem-pizza\nprice-Rs239");
	        break;
	    }
	    case(2):
        {
	        printf("food item-burger\nprice-Rs 139");
	    	break;
	    }
	    case(3):
	    {
	    	printf("food item-pasta\nprice-Rs 179");
	    	break;
	    }
	    case(4):
	    {
	    	printf("food item-french fries\nprice-Rs 99");
	    	break;
	    }
	    case(5):
	    {
	    	printf("food item-sandwich\nprice-Rs 149");
	    	break;
	    }
	    default:
	    {
	    	printf("invalid choice");
	    }
	 }
	 return 0;
}
