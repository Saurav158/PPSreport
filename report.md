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
