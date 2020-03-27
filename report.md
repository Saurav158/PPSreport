![image](https://img.collegedekhocdn.com/media/img/institute/logo/GNDEC_Ludhiana_logo.png)

# Programming for Problem solving(ESC-105)
----
Submitted by: Saurav Kumar

Class roll: 1916069

Univ roll: 1905152

Branch: Electrical Engineering

Batch: 2019-2023

Section-B
----

Experiment1 : Write a code to print your name
```C

#include<stdio.h>
int main()
{
puts("Saurav");
return 0;
}
````

Output:
Saurav
----

Experiment2 :Write a code to print FOX
````C
#include<stdio.h>
int main()
{
    puts("########    #######     ####         ####");
    puts("##      ####       ####   ###      ###");
    puts("##      ####       ####     ###  ###");
    puts("######  ####       ####       ####");
    puts("##      ####       ####     ###  ###");
    puts("##      ####       ####   ###      ###");
    puts("##         #######     ####          ####");
}
````
Output:
````
########      ########    ####                ####
##        ####        ####   ###           ###
##        ####        ####      ###     ### 
######    ####        ####          ####
##        ####        ####        ###   ###
##        ####        ####     ###         ###
##            ########     ####               ####
````
----
Experiment3 :Design a code to execute addition of two numbers.
````C
#include<stdio.h>
int main()
{
int x,y,sum=0;
scanf("%d %d",&x,&y);
sum=x+y;
printf("%d",sum);
return 0;
}
````
Output:
````
5
9
14
````
----
Experiment4 :Write a computer program in C, which takes two numbers (integers) as input and print the smaller number.
````C
{
int x,y;    
    printf("\n\t enter any two number\n");
    scanf("%d%d",&x,&y);
    if(x>y)
    {
    printf("%d",y);
    }
    else
    {
    printf("%d",x);
    }
    return 0;
}
````
Output:
````
67
54
67
````
-----
experiment5 :Write a C program to print the following character in a reverse way without using any predefined function and header file.
````C
{
#include<stdio.h>
int main()
{
char ch1,ch2,ch3;
scanf(" %c %c %c",&ch1, &ch2, &ch3);
printf(" %c%c%c is %c%c%c",ch1, ch2, ch3, ch3, ch2, ch1);
return 0;
}
````
Output:
````
RAM is MAR
````
----
Experiment6 :Write a C program to compute the perimeter and area of a rectangle with a
 height of 7 inches and width of 5 inches.
 ````C
 #include<stdio.h>
int main()
{
    int height,width,area,perimeter;
    scanf("%d%d",&height,&width);
    perimeter=2*(height+width);
    printf("Perimeter of the rectangle: %d inches\n",perimeter);
    area=height*width;
    printf("Area of the rectangle= %d square inches",area);
    return 0;
    
}
````
Output:
````
Perimeter of the rectangle: 24 inches


Area of the rectangle = 35 square inches

````
-----
Experiment7 : Design a code to execute addition of two numbers if the sum is even.


Display a message Even otherwise Odd.
````C
#include<stdio.h>
int main()
{
    int num1,num2,sum;
    scanf("%d%d",&num1,&num2);
    sum=num1+num2;
    if(sum%2==0)
    printf("Even");
    else
    printf("Odd");
    return 0;
}
````
Output:
````
52 3
Odd
````
----
experiment8 :Design a code to mark 'Present' if student entered in a hall before 8:35 and
marked 'Late' before 8:45 otherwise marked 'Absent'.


If user will enter the time between 8:00 - 8:14 then display a message 'Sorry Gate closed' 
and if user  will enter the time less than 8:00 then display a message 'Its wrong Time'.
````C
#include<stdio.h>
int main()
{
    float time;
    //time should be in the format of hh.mm
    scanf(" %f",&time);
    if(time>8.14 && time<8.36)
    printf("Present");
    else
    {
        if(time>=8.36 && time<=8.45)
        printf("Late");
        else
        {
            if(time>8.45 && time<9.00)
            printf("Absent");
            else
            {
                if(time==8.00 && time<=8.14)
                printf("Sorry Gate closed");
                else
                {
                    if(time>7.00 && time<8.00)
                printf("You entered wrong Time");
                    else
                    {
                        if(time>=9.00)
                        printf("Sorry Gate closed");
                        else
                        {
                            if(time>=1.00 && time<=7.00)
                            printf("Wrong Timing");
                        }
                    }
                }
            }
            
        }
        
    }
    return 0;
}
````
Output:
````
732                                                                             
Sorry Gate closed                                                               
````
-----
Experiment9 :Write a code to convert temperature from Fahrenheit scale to centigrade scale.
````C
#include<stdio.h>
int main()
{
    float fahrenheit,centigrade;
    //enter the temp.in fahrenheit
    scanf("%f",&fahrenheit);
   centigrade=(fahrenheit-32)*5/9;
   if(fahrenheit==56.0)
   printf(" Fahrenheit scale: %.1f \nCentigrade scale: %.2f",fahrenheit,centigrade);
   else
   printf(" Fahrenheit scale: %.2f \nCentigrade scale: %.2f",fahrenheit,centigrade);
   return 0;
    
}
````
Output:
````
67.00
Fahrenheit scale: 67.00
Centigrade scale: 19.44
``````
-----
Experiment10 :Write a code to find the factorial of a number.
```C
#include<stdio.h>
int main()
{
int num,fact=1,i;
scanf("%d",&num);
printf("%d",num);
for(i=1;i<=num;i++)
{ 
fact=fact*i;
} 
 printf("%d",fact); 
return 0; 
}
````
Output:
````
6
720
````
----
Experiment11 :write a code to play Fizzbuzz.
````C
#include<stdio.h>
int main()
{
int i;
printf("play fizz buzz");
printf("\n FIZZ BUZZ \n");
scanf("%d",&i);
if(i%3==0 && i%5==0)
printf("FIZZ BUZZ");
else
{
if(i%5==0)
printf("BUZZ");
else
{
i%3==0?printf("FIZZ"):printf("%d ",i);
}
 }
 return 0;
}
````
Output:
````
3
Fizz
15
Fizz Buzz
24
24
````
----
Experiment12 :Write a code to print table of any number.
````C
#include<stdio.h>
int main()
{
int i,num;
scanf("%d",&num);
for(int i=1;i<=10;i++)
{
printf("%d x %d=%d\n",num,i,num*i);
}
return 0;
}
````
Output:
````
12 x 1 = 12
12 x 2 = 24
 :  :  :
 :  :  :
12 x 10 = 120
`````
-----
Experiment13 :Write a code to print table between range i.e table 6 to 9.
````C
#include<stdio.h>
int main()
{
    int num1,num2,i,j;
    scanf("%d %d",&num1,&num2);
    for(i=num1;i<=num2;i++)
    {
        for(j=1;j<=10;j++)
        {
        printf("%d x %d=%d\n",num1,j,num1*j);
        }
        if(num1<num2)
        printf("_______\n\n");
        num1=num1+1;
    }
    return 0;
}
````
Output:
````
6 x 1 = 6    

6 x 2 = 12                             
. . . . .  

6 x 10 = 60        
____________

7 x 1 = 7 

7 x 2 = 14  
. . . . . 

7 x 10 = 70
____________

9 x 1 = 9 

9 x 2 = 18    
 . . . .  .   

9 x 10 = 90 
````
----
Experiment14 :Write a code to display the number is prime or not.
````C
#nclude<stdio.h>
int main()
{
    int num,a=1,i;
    scanf("%d",&num);
    for(i=2;i<=num/2;i++)
    {
        if(num%i==0)
        {
        a=0;
        break;
        }
        
    }
    if(a==1)
    printf("Number is Prime");
    else
    printf("Number is not Prime");
    
return 0;
    
}
````
Output:
````
13
Number is prime.
````
----
Experiment15 :Write a code to print a range of prime number between some range.
````C
#include<stdio.h>
int main()
{
    int num1,num2,i,j;
    scanf("%d %d",&num1,&num2);
    for(i=num1;i<=num2;i++)
    {
    for(j=2;j<i;j++)
    {
        if(i%j==0)
            break;
    }
        if(i==j)
        printf("%d \n",i);

    }

    return 0;
}
````
Output:
````
2 10
2 
3
5
7
``````
-----
Experiment16 :Write a program to swap two numbers using a temporary variable.
````C
#include<stdio.h>
int main()
{
    int x,y,temp;
    scanf("%d %d ",&x,&y);
    printf("x=%d and  y=%d are two numbers ",x,y);
    temp=x;
    x=y;
    y=temp;
    printf("x=%d and y=%d",x,y);
    return 0;
}
````
Output:
````
a=2
b=3
a=3
b=2
````
---- 
Experiment17 :Write a computer program in C, which take integer input from user. If entered value > 10, it will call a function, which prints multiplication table of of entered number, from 1 to 10, in following format:

1 x 7 = 7

2 x 7 = 14

`````
If entered value is between 6 to 10, then will be call another function, which print number of lines equal to entered number in following pattern:

    #
   #.#
  #...#
 #.....#
#.......#
`````

for any other input it will display:

Have a nice day!
`````C
#include<stdio.h>
int main()
{
int num;
printf("\n\tEnter a number\n");
scanf("%d",&num);
if(num>10)
  {
int table();
 table(num);
  }
else
  {
  if(num>=6 && num<=10)
   {
int pattern();
  pattern(num);
   }
   else
   {
 void print();
print();
   }
  }
return 0;
}
   
int table(int a)
{
int i,table;
for(i=1;i<=10;i++)
printf("%d X %d=%d \n",i,a,i*a);
}
  
  int pattern(int b)
  {
  int i,j;
  for(i=1;i<=b;i++)
  {
  for(j=1;j<=b;j++)
    {
  if(j==1 || j==i)
   printf("*");
  else
   if(j>=2 && j<=i-1)
   printf(".");
  else
  printf(" "); 
  }
  printf("\n");
 }
}
  
void print()
{
printf("Have a nice day!");
 }
 
 ````
 Output:
 `````
 3
 
 Have a nice day!
 ````
 7

     #
    #.#
   #...#
  #.....#
 #.......#
````
12
````
1 x 7 = 7

2 x 7 = 14
````
----
