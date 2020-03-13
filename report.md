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
