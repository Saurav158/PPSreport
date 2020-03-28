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
Experiment18 :Write a computer program in C, to print nth term, and sum up to nth term for series:

x−x^3/3!+x^5/5!−x^7/7!+x^9/9!−⋯

where "1" represent factorial.

No user made function or library function is to be used.
````C
#include<stdio.h>
int main()
{
int x,n;
printf("\nThe series is : x-x^3/3!+x^5/5!-......");
printf("\nEnter the value of x and n:");
scanf("%d %d",&x,&n);
int i,m;
float sum=0,a,b,c;
for(i=1;i<=n;i++)
   {
   m=((2*1)-1);
   a=pow(x,m);
   b=fact(m);
   c=a/b;
   if(i%2==0)
   sum=sum-c;
   else
   sum=sum+c; 
   }
printf(" thye nth term is %d^%d/%d!",x,m,m);   
printf(" the sum of nth term is %0.3f\n",sum);
return 0;
}

int pow(int a,int b)
{
int p=1,i=1;
while(b!=0)
   {
    p=p*a;
    b--;
   }
return (p);
}

int fact(int n)
{
int i,f=1;
for(i=n;i>1;i--)
  {
   f=f*i;
  }
return (f);
}
````
````
Output: 
3
3
the nth term is 3^5/5!

the sum of nth term is 0.525
````
----
Experiment19 :game of life
````C
#include <stdio.h>
#include <stdlib.h>
#include <unistd.h>
#include <time.h>
#include <sys/ioctl.h>


/**
 * Count a cell's neighbours simulating a torique matrix
 * If we hit the size of the grid then we check the opposite side.
 */
int get_neighbours(int ** grid, int i, int j, int l_size, int c_size)
{
  int n = 0;
  
  n += grid[i][(j + 1) > (c_size - 1) ? 0 : (j + 1)];
  n += grid[i][(j - 1) >= 0 ? (j - 1) : (c_size - 1)];
  
  n += grid[(i + 1) > (l_size - 1) ? 0 : (i + 1)][j];
  n += grid[(i - 1) >= 0 ? (i - 1) : (l_size - 1)][j];
  
  n += grid[(i + 1) > (l_size - 1) ? 0 : (i + 1)][(j + 1) > (c_size - 1) ? 0 : (j + 1)];
  n += grid[(i + 1) > (l_size - 1) ? 0 : (i + 1)][(j - 1) >= 0 ? (j - 1) : (c_size - 1)];

  n += grid[(i - 1) >= 0 ? (i - 1) : (l_size - 1)][(j + 1) > (c_size - 1) ? 0 : (j + 1)];
  n += grid[(i - 1) >= 0 ? (i - 1) : (l_size - 1)][(j - 1) >= 0 ? (j - 1) : (c_size - 1)];
  
 
  return n;
}

/**
 * Swap two array of two dimensions.
 */
void swap_grid(int *** grid_old, int *** grid_new)
{
  int ** tmp = *grid_old;
  *grid_old = *grid_new;
  *grid_new = tmp;
}

/**
 * Simulate the world and calculate the next generation of cells.
 */
void update_grid(int *** grid_old, int *** grid_new, int l_size, int c_size)
{
  int i, j, n;
 
  for (i = 0; i < l_size; i++){
    for (j = 0; j < c_size; j++){
      n = get_neighbours(*grid_old, i, j, l_size, c_size);
      if((*grid_old)[i][j]){ // alive
	(*grid_new)[i][j] = (n == 3 || n == 2 );
      }else { // dead cell
	(*grid_new)[i][j] = (n == 3);
      }
    }
  }
  
  swap_grid(grid_old, grid_new);

}

/**
 * Display the grid, change the output here.
 */
void display_grid(int ** grid, int l_size, int c_size)
{
  int i, j;
  for (i = 0; i < l_size; i++){
    for (j = 0; j < c_size; j++){
      if(grid[i][j]){
	printf("O");
      } else {
	printf(".");
      }     
    }
    printf("\n");
  }  
}

/**
 * Initialise a random grid with the size given.
 */
int ** init_grid(int l_size, int c_size, int alea_percent)
{
  int i, j;
  int ** grid = malloc(sizeof(*grid) * l_size);
  
  for (i = 0; i < l_size; i++){
    grid[i] = malloc(sizeof(**grid) * c_size);
  }

  srand(time(NULL));
  
  for (i = 0; i < l_size; i++){
    for (j = 0; j < c_size; j++){
      grid[i][j] = ((rand()%100+1) <= alea_percent);
    }
  }  
  return grid;
}

void free_grid(int ** grid, int l_size)
{
  int i;
  for(i = 0; i < l_size; i++){
    free(grid[i]);
  }
  free(grid);
}

int is_integer(char *string)
{
  char c;
  int i;

  for(i = 0; string[i] != 0; i++){
      c = string[i];
      if(c < '0' || c > '9'){
          return 0;
      }
  }
  return 1;
}

void handle_arg(int argc, char **argv, int *l_size, int *c_size, int *wait_time, int *alea_percent)
{
  char *options = "r:c:t:a:h";
  int current_option;
  char help[512];

  snprintf(help, 512, "Usage\n %s [OPTIONS]\n\nThe following options are availables:\n"
  "-h,          Show this help menu\n"
  "-r,          Set the number of row (5 min)\n"
  "-c,          Set the number of colomns (5 min)\n"
  "-t,          Set the time between each frame update (in microseconds)\n"
  "-a,          Set the percentage of cells apparition on initialistion(100 max)\n", argv[0]);


  while((current_option = getopt(argc, argv, options)) != -1){
    int *opt_addr;    
    
    switch(current_option){    
        case 'r': opt_addr = l_size; break;
        case 'c': opt_addr = c_size; break;
        case 't': opt_addr = wait_time; break;
        case 'a': opt_addr = alea_percent; break;
        case 'h': printf("%s", help); exit(0);
    }

    if(optarg != NULL){
        // The argument is a valid integer.
        if(is_integer(optarg)){
          if((current_option == 'r' || current_option == 'c') && (atoi(optarg) < 5)){
            fprintf(stderr, "Error: The minimum size for -%c is 5.\n", current_option);
            exit(-1);
          }
          if(current_option == 'a' && (atoi(optarg) > 100)){
            fprintf(stderr, "Error: The maximum value for -%c is 100.\n", current_option);
            exit(-1);
          }
          if(current_option == 't' && (atoi(optarg) < 0)){
            fprintf(stderr, "Error: The value for -%c should be positive.\n", current_option);
            exit(-1);
          }
        *opt_addr = atoi(optarg);
        } else {
            fprintf(stderr, "Error: The value for -%c should be an integer.\n", current_option);
            exit(-1);
        }
    } else {
        exit(-1);
    }
  }
}

int main(int argc, char * argv[])
{
  int l_size, c_size, counter, wait_time, alea_percent;
  int ** grid, ** grid_tmp;
 
  struct winsize w;
  ioctl(STDOUT_FILENO, TIOCGWINSZ, &w);

  counter = 0;
  wait_time = 100;
  alea_percent = 15;
  l_size = w.ws_row-2;
  c_size = w.ws_col;

  // Get the options.
  handle_arg(argc, argv, &l_size, &c_size, &wait_time, &alea_percent);
  
  // Initialization.
  grid = init_grid(l_size, c_size, alea_percent);
  grid_tmp = init_grid(l_size, c_size, alea_percent);
  
  // Game loop.
  while(1){
    
    printf("\nCycle %d\n", ++counter);
    display_grid(grid, l_size, c_size);
    usleep(wait_time * 1000);     
    update_grid(&grid, &grid_tmp, l_size, c_size);
    
  }
  
  free_grid(grid, l_size);
  free_grid(grid_tmp, l_size);
  
  return 0;
}
````
````
Output:
`````
![img1](https://cloud.githubusercontent.com/assets/9862039/26368958/3d00a16e-3fc1-11e7-9b0c-9fed3befa812.png)

----
