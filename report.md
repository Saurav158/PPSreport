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
experiment :Write a C program to print the following character in a reverse way without using any predefined function and header file.
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
Experiment:Write a C program to compute the perimeter and area of a rectangle with a
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
Experiment: Design a code to execute addition of two numbers if the sum is even.


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
experiment:Design a code to mark 'Present' if student entered in a hall before 8:35 and
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
Experiment:Write a code to convert temperature from Fahrenheit scale to centigrade scale.
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
Experiment:Write a code to find the factorial of a number.
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
Experiment:write a code to play Fizzbuzz.
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
Experiment: 
