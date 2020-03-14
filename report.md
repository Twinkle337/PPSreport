![gne](https://raw.githubusercontent.com/Twinkle337/PPSreport/master/321.jpg)
# Programming For Problem Solving(ESC-105)
------
Submitted By: Twinkle

Class RollNo: 1916080

University Rollno: 1905162

Branch:Electrical

Batch: 2019-2023

Section:B

---------------

Experiment No.1:
Write a code to print name of the college.

```C
#include<stdio.h>
int main();
{
puts("welcome you in gndec");
}
```
----------

Experiment No.2:
Write a code to print hello.

 ```C
 #include<stdio.h>
int main()
{
    puts("hello");
    
}
```
--------------
Experiment No.3:
Write a code to print big c.

```C
#include<stdio.h>
int main()
{
    puts(" ######");
puts("##    ##");
puts("#");
puts("#");
puts("#");
puts("#");
puts("#");
puts("##    ##");
puts(" ######");
}
```
------------
Experiment No.4
write a code to print addition of two numbers.

```C
#include <stdio.h>
int main()
{
  int x, y, z;

  printf("Enter two numbers to add\n");
  scanf("%d%d", &x, &y);

  z = x + y;

  printf("Sum of the numbers = %d\n", z);

  return 0;
}
```
-----------

Experiment No.5
write a code to print the smallest number.

```C
#include<stdio.h>
int main()
{
  int a[10], Size, i, Smallest, Position;
  
  printf("\nPlease Enter the size of an array \n");
  scanf("%d",&Size);

  printf("\nPlease Enter %d elements of an array: \n", Size);
  for(i=0; i<Size; i++)
   {
   	 scanf("%d",&a[i]);
   }   

  Smallest = a[0];
  for(i=1; i<Size; i++)
   {
    if(Smallest > a[i])
     {
       Smallest = a[i];
       Position = i;
	 }   
   }
  
  printf("\nSmallest element in an Array = %d", Smallest);
  printf("\nIndex position of the Smallest element = %d", Position);
  
  return 0;
}
```
-------

Experiment No.6:
Write a code to print the character in a reverse way.

```C
#include <stdio.h> 
 int main() 
 {
    char char1 = 'X';
    char char2 = 'M';
    char char3 = 'L';

	printf("The reverse of %c%c%c is %c%c%c\n",
		char1, char2, char3,
		char3, char2, char1);

	return(0);
}
```
--------

Experiment No.7:
Write a code to print rectangle.

```C
/**
 * C program to print rectangle star pattern
 */

#include <stdio.h>

int main()
{
    int i, j, rows, columns;

    /* Input rows and columns from user */
    printf("Enter number of rows: ");
    scanf("%d", &rows);
    printf("Enter number of columns: ");
    scanf("%d", &columns);

    /* Iterate through each row */
    for(i=1; i<=rows; i++)
    {
        /* Iterate through each column */
        for(j=1; j<=columns; j++)
        {
            /* For each column print star */
            printf("*");
        }
        
        /* Move to the next line/row */
        printf("\n");
    }

    return 0;
}
```
---------

Experiment No.8:
Write a code to check the timing.

```C
#include <stdio.h>
     
     clock_t start, end;
     double cpu_time_used;
     
     start = clock();
     ... /* Do the work. */
     end = clock();
     cpu_time_used = ((double) (end - start)) / CLOCKS_PER_SEC;
```
---------

Experiment No.9:
Write a code to print farnehite to centigrade.

```C
#include<stdio.h>
Int main()
{
    float c,f;
    clrscr();
    printf("Enter the Temperature in farnehite: ");
    scanf("%c",&f);
    C=(5.0/9)* (f-32.0);
    printf("Temparature in centigrate is : %f"\n",c);
    return 0;
}
```
----------

Experiment No.10:
Write a code to print a factorial. 

```C
#include <stdio.h>
 
int main()
{
  int c, n, f = 1;
 
  printf("Enter a number to calculate its factorial\n");
  scanf("%d", &n);
  for (c = 1; c <= n; c++)
    f = f * c;
 
  printf("Factorial of %d = %d\n", n, f);
 
  return 0;
}
```
------------

Experiment No.11:
Write a code to print table of any number.

```C
#include<stdio.h>
Int main()
{
int i,no,table=1;
clrscr();
printf("Enter any number : ");
scanf("%d",&no);
printf("Table of  %d \n",no);
for(i=1;i<=10;i++)
{
table=no*i;
printf("%d",table);
printf("\n");
}
getch();
}
```
------------

Experiment No.12:
Write a code to print prime numbers.

```C
#include <stdio.h>
int main()
{
  int n, i = 3, count, c;

  printf("Enter the number of prime numbers to print\n");
  scanf("%d", &n);

  if (n >= 1) {
    printf("First %d prime numbers are:\n",n);
    printf("2\n");
  }

  for (count = 2; count <= n;)
  {
    for (c = 2; c <= i - 1; c++)
    {
      if (i%c == 0)
        break;
    }
    if (c == i)
    {
      printf("%d\n", i);
      count++;
    }
    i++;
  }

  return 0;
}
```
----------

Experiment No.13:
Write a code to print Swap Numbers Without Using Temporary Variables. 

```C
#include <stdio.h>
int main() {
    double a, b;
    printf("Enter a: ");
    scanf("%lf", &a);
    printf("Enter b: ");
    scanf("%lf", &b);

    // Swapping process
    a = a - b;
    b = a + b;
    a = b - a;

    printf("After swapping, a = %.2lf\n", a);
    printf("After swapping, b = %.2lf", b);
    return 0;
}
```
------------

Experiment NO.14:
Write a code to print Program to find Area, Perieter, Volume of a Circle.

```C
#include<stdio.h>
int main()
{
float r,P,A,V;
float pi = 22/7.0;
printf("\nEnter The Radius of Circle: ");
scanf("%f",&r);
P = 2*pi*r;
A = pi*r*r;
V = 4*pi*r*r*r/3.0;
printf("\nPerimeter of Circle is: = %.2f",P);
printf("\nArea of Circle is: = %.2f",A);
printf("\nVolume of Circle is: = %.2f",V);
return 0;
}
```
-----------

Experiment No.15:
Write a code to print Program to find Area, Perimeter of a Rectangle.

```C
#include<stdio.h>
int main()
{
float h,b,A,P;
printf("\nEnter Height: ");
scanf("%f",&h);
printf("\nEnter Bredth: ");
scanf("%f",&b);
A = h*b;
P = 2*(h+b);
printf("\nArea of Sqare (or) Rectangle: = %.3f",A);
printf("\nPerimeter of Sqare (or) Rectangle: = %.3f",P);
return 0;
}
```
------------

Experiment No.16:
Write a code to print Program to find Interest.

```C
#include<stdio.h>
int main()
{
float P,R,T,Interest;
printf("\nEnter The Principal Amount: ");
scanf("%f", &P);
printf("\nEnter The Interest Rate: ");
scanf("%f", &R);
printf("\nEnter The Time (in months): ");
scanf("%f", &T);
Interest = P*T*R/100;
printf("\nSimple Intesest is: = %.2f", Interest);
return Interest;
}
```
-------

Experiment No.17:
Write a code to print Program to find Maximum. 

```C
#include<stdio.h>
int max(float x,float y);
int main()
{
float x,y,z;
printf("\nEnter The First Value: ");
scanf("%f",&x);
printf("\nEnter The Second Value: ");
scanf("%f",&y);
z = max(x,y);
printf("\nMaximum value is: %.2f\n", z);
return 0;
}
int max(float x,float y)
{
float result;
if(x<y)
result = y;
else
result = x;
return result;
}
```
------------

Experiment No.18:
Write a code to print Program to find a Power of a Number.

```C
#include<stdio.h>
int main()
{
int base,power,ans=1;
printf("\nEnter base number: ");
scanf("%d",&base);
printf("Enter exponent(power): ");
scanf("%d",&power);
while (power!=0)
{ ans *= base;
power--; }
printf("Answer = %d\n", ans);
return 0;
}
```
-----------

Experiment No.19:
Write a code to print Program to take 5 values from the user and store them in an array and Print
the elements.

```C
#include<stdio.h>
int main()
{
int x,array[5];
printf("\n");
for(x=1;x<=5;x++)
{ printf("Enter [%d] element: ", x);
scanf("%d", &array[x]); }
for(x=1;x<=5;x++)
{ printf("\nElement [%d] = %d", x, array[x]); }
return 0;
}
```
----------





 
