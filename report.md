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

# INDEX

1. Write a code to print name of college.
2. Write a code to print hello.
3. Write a code to print big c.
4. Write a code to print addition of two numbers.
5. Write a code to print the smallest number.
6. Write a code to print the character in a reverse way.
7. Write a code to print the rectangle.
8. Write a code to print check the timing.
9. Write a code to print farnehite to centigrade.
10. Write a code to print a factorial.
11. Write a code to print the table of any number.
12. Write a code to print prime numbers.
13. Write a code to print swap numbers without using temperary variables.
14. Write a code to print program to find area,perimeter and volume of a circle.
15. Write a code to print program to find area,perimeter and volume of rectangle.
16. Write a code to print program to find Interest.
17. Write a code to print program to find Maximum.
18. Write a code to print program to find a power of a number.
19. Write a code to print program to take 5 values from the user and store them in an array and print the elements.
20. Write a code to print program to use arithmetic Operators.
21. Write a code to print program to use assignment Operators.
22. Write a code to print program to use Operator Precedence.
23. Write a code to print program to find Average.
24. Write a code to print program to find fizz buzz odd a integer.
25. Write a code to print Program of Addition of 2x2 Matrix.
26. Write a code to print Program of FizzBuzz in a continues loop.
27. Write a code to print Program to print a Pyramid.
28. Write a code to print  Program to implement Linear search for One Dimensional array.
29. Write a code to print Program to find weather the Number is Even or Odd using if-else statement.
30. Write a code to print Program to find Sum of First 10 Natural Numbers using for loop.
31. Write a code to print Program to implement a life game.

-------------

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
Write a code to print Program to find Area, Perimeter, Volume of a Circle.

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

Experiment No.20:
Write a code to print Program to use Arithmetic Operators.

```C
#include<stdio.h>
int main()
{
float x,y,a;
printf("\nEnter The Value of x: ");
scanf("%f",&x);
printf("\nEnter The Value of y: ");
scanf("%f",&y);
a = x+y;
printf("x + y = %.3f\n",a);
a = x-y;
printf("x - y = %.3f\n",a);
a = y-x;
printf("y - x = %.3f\n",a);
a = x*y;
printf("x * y = %.3f\n",a);
a = x/y;
printf("x/y = %.3f\n",a);
a = y/x;
printf("y/x = %.3f\n",a);
return 0;
}
```
------------

Experiment No.21:
Write a code to print Program to use Assignment Operators.

```C
#include<stdio.h>
int main()
{
float x,a;
printf("\nEnter The Value of x: ");
scanf("%f",&x);
a = x;
printf("Answer is a = x %.3f\n",a);
a +=x; //answer is a+x
printf("Answer is a+x = %.3f\n",a);
a -=x; //answer is a-x
printf("Answer is a-x = %.3f\n",a);
a *=x; //answer is a*x
printf("Answer is a*x = %.3f\n",a);
a /=x; //answer is a/x
printf("Answer is a/x= %.3f\n",a);
return 0;
}
```
------------

Experiment No.22:
Write a code to print Program to use Operator Precedence.

```C
#include<stdio.h>
int main()
{
float a,b,c,d,A;
printf("\nEnter The Value of a: ");
scanf("%f",&a);
printf("Enter The Value of b: ");
scanf("%f",&b);
printf("Enter The Value of c: ");
scanf("%f",&c);
printf("Enter The Value of d: ");
scanf("%f",&d);
A = (a+b)*(c+d);
printf("\n (a+b)*(c+d) = %.3f",A);
A = (c+d)*a*b;
printf("\n (c+d)*a*b = %.3f",A);
A = a*d/(c-b-a);
printf("\n a*d/(c-b-a) = %.3f",A);
A = (b-c)*(a-d);
printf("\n (b-c)*(a-d) = %.3f",A);
return 0;
}
```
------------

Experiment No.23:
Write a code to print Program to find Average.

```C
#include<stdio.h>
int main()
{
int x,N;
float avg[1000],s,ans;
printf("\nEnter the Number of elements: ");
scanf("%d", &N);
printf("\n");
for(x=1; x<=N; x++)
{ printf("Enter [%d] element: ", x);
scanf("%f", &avg[x]);
s += avg[x]; }
ans = s/N;
printf("\nAverage of %d elements = %.3f", N, ans);
return 0;
}
```
--------------

Experiment No.24:
Write a code to print Program to find FizzBuzz odd a Integer.

```C
#include<stdio.h>
int main()
{
int n;
printf("\nEnter the Interger: ");
scanf("%d",&n);
if(n%15==0)
printf("\nFizzBuzz");
else if(n%3==0)
printf("Fizz\n");
else if (n%5==0)
printf("\nBuzz");
else
printf("\n%d",n);
return 0;
}
```
-------------

Experiment No.25:
Write a code to print Program of Addition of 2x2 Matrix.

```C
#include<stdio.h>
int main()
{
float a,b,c,d,e,f,g,h,i,j,k,l;
printf("\nSample of Ist matrix: | a=1 b=2 |\n | c=3
Sample of 2nd matrix: | e=5 f=6 |\n | f=7 h=8
printf("Enter The Valve of a: ");
scanf("%f",&a);
printf("Enter The Valve of b: ");
scanf("%f",&b);
printf("Enter The Valve of c: ");
scanf("%f",&c);
printf("Enter The Valve of d: ");
scanf("%f",&d);
printf("Enter The Valve of e: ");
scanf("%f",&e);
printf("Enter The Valve of f: ");
scanf("%f",&f);
printf("Enter The Valve of g: ");
scanf("%f",&g);
printf("Enter The Valve of h: ");
scanf("%f",&h);
i = a+e;
j = b+f;
k = c+g;
l = d+h;
printf("\n\nSum of Matrix(A+B) is: | %.2f %.2f |\n
i = a-e;
j = b-f;
k = c-g;
l = d-h;
printf("\n\nSubstraction of Matrix(A-B) is: | %.2f %.2f |\n
i = e-a;
j = f-b;
k = g-c;
l = h-d;
printf("\n\nSubstraction of Matrix(B-A) is: | %.2f %.2f |\n
return 0;
}
```
---------------

Experiment No.26:
Write a code to print Program of FizzBuzz in a continues loop. 

```C
#include<stdio.h>
int main()
{
int n,x;
printf("\nEnter The Integer: ");
scanf("%d",&n);
printf("\n");
{
for(x=1;x<=n;x++)
if(x%15==0)
printf("FizzBuzz\n");
else if(x%3==0)
printf("Fizz\n");
else if(x%5==0)
printf("Buzz\n");
else
printf("%d\n",x);
}
return 0;
}
```
----------

Experiment No.27:
Write a code to print Program to print a Pyramid.

```C
#include<stdio.h>
int main()
{
int i,j,n;
printf("\nEnter number of Rows: ");
scanf("%d",&n);
printf("\n");
for(i=1; i<=n; i++)
{
for(j=1; j<=2*n-1; j++)
{
if(j>=n-(i-1) && j<=n+(i-1))
printf("*");
else
printf(" ");
}
printf("\n");
}
return 0;
}
```
---------------

Experiment No.28:
Write a code to print  Program to implement Linear search for One Dimensional array.

```C
#include<stdio.h>
int main()
{
int array[12]={1,5,9,7,3,82,46,23,23,5,10,3};
int size=12,flag=0,item,a;
printf("\nEnter the Value: ");
scanf("%d", &a);
for(int i=0;i<size;i++)
{
if(a==array[i])
{
flag=a;

break;
}
}
if(flag==a)
printf("\nSearch is Sucessfull \n%d Element is present in the array\n",a);
else
printf("\nSearch is Unsucessfull \n%d Element is not present in the array\n",a
return 0;
}
```
------------

Experiment No.29:
Write a code to print Program to find weather the Number is Even or Odd using if-else statement. 

```C
#include<stdio.h>
int main()
{
int x;
printf("\n\nEnter the Number: ");
scanf("%d", &x);
if(x%2==0)
printf("%d is Even", x);
else
printf("%d is Odd", x);
return 0;
}
```
-------------

Experiment No.30:
Write a code to print Program to find Sum of First 10 Natural Numbers using for loop. 

```C
#include<stdio.h>
int main()
{
int x,ans;
for(x=1;x<=10;x++)
{ ans += x; }
printf("\n\nSum of first 10 Nmubers: %d",ans);
return 0;
}
```
----------------

Experiment No.31:
Write a code to print a to implement a life game.

```C

// A simple C# program to implement 
// Game of Life 

using System; 

  

public class GFG { 

      

    public static void Main() 

    { 

        int M = 10, N = 10; 

  

        // Intiliazing the grid. 

        int[,] grid = { 

            { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 }, 

            { 0, 0, 0, 1, 1, 0, 0, 0, 0, 0 }, 

            { 0, 0, 0, 0, 1, 0, 0, 0, 0, 0 }, 

            { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 }, 

            { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 }, 

            { 0, 0, 0, 1, 1, 0, 0, 0, 0, 0 }, 

            { 0, 0, 1, 1, 0, 0, 0, 0, 0, 0 }, 

            { 0, 0, 0, 0, 0, 1, 0, 0, 0, 0 }, 

            { 0, 0, 0, 0, 1, 0, 0, 0, 0, 0 }, 

            { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 } 

        }; 

  

        // Displaying the grid 

        Console.WriteLine("Original Generation"); 

        for (int i = 0; i < M; i++) 

        { 

            for (int j = 0; j < N; j++) 

            { 

                if (grid[i,j] == 0) 

                    Console.Write("."); 

                else

                    Console.Write("*"); 

            } 

            Console.WriteLine(); 

        } 

        Console.WriteLine(); 

        nextGeneration(grid, M, N); 

    } 

  

    // Function to print next generation 

    static void nextGeneration(int [,]grid, 

                               int M, int N) 

    { 

        int[,] future = new int[M,N]; 

  

        // Loop through every cell 

        for (int l = 1; l < M - 1; l++) 

        { 

            for (int m = 1; m < N - 1; m++) 

            { 

                  

                // finding no Of Neighbours 

                // that are alive 

                int aliveNeighbours = 0; 

                for (int i = -1; i <= 1; i++) 

                    for (int j = -1; j <= 1; j++) 

                        aliveNeighbours +=  

                                grid[l + i,m + j]; 

  

                // The cell needs to be subtracted 

                // from its neighbours as it was  

                // counted before 

                aliveNeighbours -= grid[l,m]; 

  

                // Implementing the Rules of Life 

  

                // Cell is lonely and dies 

                if ((grid[l,m] == 1) &&  

                            (aliveNeighbours < 2)) 

                    future[l,m] = 0; 

  

                // Cell dies due to over population 

                else if ((grid[l,m] == 1) &&  

                             (aliveNeighbours > 3)) 

                    future[l,m] = 0; 

  

                // A new cell is born 

                else if ((grid[l,m] == 0) && 

                            (aliveNeighbours == 3)) 

                    future[l,m] = 1; 

  

                // Remains the same 

                else

                    future[l,m] = grid[l,m]; 

            } 

        } 

  

        Console.WriteLine("Next Generation"); 

        for (int i = 0; i < M; i++) 

        { 

            for (int j = 0; j < N; j++) 

            { 

                if (future[i,j] == 0) 

                    Console.Write("."); 

                else

                    Console.Write("*"); 

            } 

            Console.WriteLine(); 

        } 

    } 
} 
```








 
