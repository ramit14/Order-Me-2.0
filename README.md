# Order-Me-2.0
Developed by Ramit Bhanawat.
#include<stdio.h>
main()
{
printf("pick an item : \n1. panner chilli\n2. manchurian\n3. alfredo\n4. fried rice");
int choice=0;
scanf("%d,&choice);
switch(choice)
{
case 1:
printf("you picked panner chilli");
break;
case 2:
printf("you picked manchurian");
break;
case 3:
printf("you picked alfredo");
break;
case 4:
printf("you picked fried rice");
break;
default : printf("invalid choice , try again");
}
]
