 
<center><img src="https://i.imgur.com/EZtECRw.png"></center>

---

<h3><b>Guru Nanak Dev Engineering College
         ESC-18104/18105 Programming for Problem Solving</b>
  
  
     
            Name-Manpreet kaur
            Branch-InformationTechnology
            Section - A2 
            Roll Number - 1921062
            
            Submitted to - Prof.Ranjodh Kaur
    
    ## Pps assignment

## 1:Write a program to calculate experience of employees

```
/#include<stdio.h>
int main()
{
 int n,yr,sum=0;
 printf("\n enter number of employees");
 scanf("%d",&n);
 for(int i=1;i<=n;i++)
{
 printf("\n Enter the number of years of experience of %d employee:\n ",i);
 scanf("%d",&yr);
 sum=sum+yr;
}
printf("Total experience is : %d\n",sum);
return 0;
}

```
**OUTPUT:**
``` 
  enter number of employees2

 Enter the number of years of experience of 1 employee:
 6

 Enter the number of years of experience of 2 employee:
 3
Total experience is : 9

```
## 2:Write a program to fill your information

```
  
#include<stdio.h>

  void info();
  int main()
  {
     info();
  }

   void info()
  {  char a[20];
     int roll,age;
     long int ph;
   printf("\nEnter your information:\n");
   printf("Name = ");
    scanf("%s",a);
  printf("\nRoll no=");
scanf("%d",&roll);
printf("\nAge = ");
 scanf("%d",&age);
 printf("\nPhone no.= ");
 scanf("%ld",&ph);

printf("\nThe name is %s\nYour roll no is %d\nMy phone number is %ld\n My age is %d\n",a,roll,ph,age);

}
```
**OUTPUT:**
```
Enter your information:
Name = Raman

Roll no=19753

Age = 20

Phone no.= 9877456788

The name is Raman
Your roll no is 19753
My phone number is 9877456788
 My age is 20
 ```

## 3:Write a program to check whether the number is positive or negative
```
    #include<stdio.h>
int main()
{
 int a;
 printf("Enter the number to be checked ");
 scanf("%d",&a);
 if(a>0)
 {
  printf("Number is positive");
 }
  else if(a<0)
 {
 printf("Number is negative");
 }
 else{
 printf("Number is zero");
 }
 return 0;
printf("\n");
}
```
**OUTPUT**:
```
Enter two number to be checked 5
 
Number is positive
```
## 4:Write a program to find sum and average of numbers
```
#include<stdio.h>
  int main()
 {                                 
     int a,b,c,d,e,sum,avg;
                                                               
   printf("Enter five numbers:");
   scanf("%d %d %d %d %d",&a,&b,&c,&d,&e);
    sum = a+b+c+d+e;
   printf("The sum is:%d\n",sum);
   avg = sum/5;
   printf("The average is:%d\n",avg);
  }
``` 
**OUTPUT**:
```
Enter five numbers:1 2 3 4 5 
The sum is:15
The average is:3
```
  ## 5:Write a program to find number is even or odd
  ```
       #include<stdio.h>
int main()
 {                                
    int a;   
   printf("Enter a number:");
   scanf("%d",&a);
 if(a%2==0)
  printf("The  number is even\n");
 else
   printf("The number is odd\n");
 }
```
**OUTPUT**:
```
Enter a number:8
The  number is even
```
***OR***
```
Enter a number:5
The number is odd
```
## 6:Write a program to find the reverse of a number
```
 #include<stdio.h>
int main()
{
 int no,rem,rev,x; 
 printf("Enter the number");
scanf("%d",&x);
no=x;
while(x>0)
{ 
  rem=x%10;
 rev=(rev*10)+rem;
 x= x/10;
}
printf("Reverse of %d is %d\n ",no,rev);
return 0;
}
```
**OUTPUT**:
```
Enter the number481
Reverse of 481 is 184
```
## 7:Write a program to show puts value upto n number using loop
```
 #include<stdio.h>
 int main()
 {
 int i,a;
 printf("Enter the number upto punishment is shown:");
 scanf("%d",&a);
  for(i=1;i<=a;i++)
puts("WORK HARD AND ACHIEVE SUCCESS ");
return 0;
}
```
**OUTPUT**:
```
Enter the number upto punishment is shown:10
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS
```
## 8:Write a program to show area,perimeter,volume of square
```
 
  #include<stdio.h>
void square();
int main()
{     
 square();
 return 0;
}                                    
void square()
{
 int side;
 printf("Enter the side of square:");
 scanf("%d",&side);

 printf("\nPerimeter of square:%d",4*side);
 printf("\nArea of square:%d",side*side);
 printf("\nVolume of square:%d\n",side*side*side);
}
```
**OUTPUT**:
```
Enter the side of square:2

Perimeter of square:8
Area of square:4
Volume of square:8
```
## 9:Write a program to show area,diameter,circumference of circle 
```
   #include<stdio.h>
 int main()
  {
    float a;   
float  const pi=3.14;
   printf("Enter radius of circle:");
    scanf("%f\n",&a);
  printf("diameter of circle is:%.2f\n",2*a);
  printf("circumference of circle:%.2f\n",2*pi*a);
  printf("Area of circle:%.2f\n",pi*a*a);
return 0;
 } 
```
**OUTPUT**:
```
Enter radius of circle:3
diameter of circle is:6.00
circumference of circle:18.85
Area of circle:28.26
```
## 10:Write a program to find area and volume of rectangle
```
#include<stdio.h>
int main()
{
 int l,b,h;
 printf("Enter length of rectangle:");
 scanf("%d",&l);
 printf("\nEnter breadth of rectangle:");
 scanf("%d",&b);
 printf("\nEnter height of rectangle:");
 scanf("%d",&h);
 printf("\nThe area of rectangle is:%d",l*b);
 printf("\nThe volume is :%d\n",l*b*h);
 return 0;
 }
 ```
 **OUTPUT**:
 ```
 Enter length of rectangle:2 

Enter breadth of rectangle:4

Enter height of rectangle:3

The area of rectangle is:8
The volume is :24
```
 
 ##  11:Write a program to convert Fahrehnite to Celcius
```
#include<stdio.h>
int main(){
float f,c;
printf("Enter temp in fahrehnite :");
scanf("%f",&f);
c=((f-32)*5)/9;
printf("The celcius value is:%f\n",c);

return 0;
}
```
**OUTPUT**:
```
Enter temp in fahrehnite :450
The celcius value is:232.222229
```
## 12:Write a program to represent a table of user input 
 
 ```

 #include<stdio.h>
 int main()
 {
    int i,j,k;
  printf("Table of:");
  scanf("%d",&j);

   for(i=0;i<=10;i++)
   printf("%d x %d = %d\n",j,i,j*i);

return 0;
}
```
**OUTPUT**:
```Table of:15
15 x 0 = 0
15 x 1 = 15
15 x 2 = 30
15 x 3 = 45
15 x 4 = 60
15 x 5 = 75
15 x 6 = 90
15 x 7 = 105
15 x 8 = 120
15 x 9 = 135
15 x 10 = 150
```
## 13: Write a program to show the table range 
```

#include<stdio.h>
int main()
{
 int a,b,i,x;
 printf("Enter the starting no. and ending no.");
 scanf("%d%d",&a,&b);
 for(i=a;i<=b;i++)
 {
 for(x=1;x<=10;x++)
{ 
 printf("\n %d X %d = %d",i,x,i*x);
}
}
 return 0;
}

```
**OUTPUT**:
```
table of:5Enter the starting no. and ending no.2 3

 2 X 1 = 2
 2 X 2 = 4
 2 X 3 = 6
 2 X 4 = 8
 2 X 5 = 10
 2 X 6 = 12
 2 X 7 = 14
 2 X 8 = 16
 2 X 9 = 18
 2 X 10 = 20
 3 X 1 = 3
 3 X 2 = 6
 3 X 3 = 9
 3 X 4 = 12
 3 X 5 = 15
 3 X 6 = 18
 3 X 7 = 21
 3 X 8 = 24
 3 X 9 = 27
 3 X 10 = 30
 ```
## 14:Write a program to show even table
```

#include<stdio.h>
int main()
{
 int a,b,i,x;
 printf("Enter the starting and ending number");
 scanf("%d%d",&a,&b);
 for(i=a;i<=b;i++)
 {
   if(i%2==0)
   {
    for(x=1;x<=10;x++)  
     {
      printf("\n%d X %d = %d ",i,x,i*x);
     }
  }
}
return 0;
} 


```
**OUTPUT**:
```
Enter the starting and ending number2 5

2 X 1 = 2 
2 X 2 = 4 
2 X 3 = 6 
2 X 4 = 8 
2 X 5 = 10 
2 X 6 = 12 
2 X 7 = 14 
2 X 8 = 16 
2 X 9 = 18 
2 X 10 = 20 
4 X 1 = 4 
4 X 2 = 8 
4 X 3 = 12 
4 X 4 = 16 
4 X 5 = 20 
4 X 6 = 24 
4 X 7 = 28 
4 X 8 = 32 
4 X 9 = 36 
4 X 10 = 40 
```
## 15: Write a program to show result of operands
```

#include<stdio.h>
int main()
{
float a,b;
 char c;
printf("enter first  number:");
scanf("%f",&a);
printf("enter operator[+ - % / *]:");
scanf(" %c",&c);
printf("enter second number:");
scanf("%f",&b);
int d,r;
d=(int) a;
r=(int) b;
switch(c)
{
case '+': printf("The result is:%.2f\n",a+b); break;
case '-':printf("The result is:%.2f\n",a-b); break;
case '*':printf("The result is:%.2f\n",a*b); break;
case '%':printf("The result is:%d\n",d%r); break;
case '/':printf("The result is:%.2f\n",a/b); break;
default : printf("Enter correct operator ");
}
return 0;
}
```

**OUTPUT**:
```
enter first  number:8
enter operator[+ - % / *]: *
enter second number:10
The result is:80.00
```
## 16:Write a progrma to call a patterns of face and calculator
```
#include<stdio.h>

void calculator();
void face();
int main()
{  int a;
 printf("enter 0 to see a calculator or 1 to see face\n");
 scanf("%d",&a);

if(a==0)
{
   calculator();
}
   else if(a==1)
{
     face();
  }
 else
{
  printf("enter correct values\n");
}
}
 void calculator()
{ 
puts(" _______________");
puts("|               |");
puts("|_______________|");
puts("| 1 | 2 | 3 |   |");
puts("|___|___|___|   |");
puts("| 4 | 5 | 6 | + |");
puts("|___|___|___|___|");
puts("| 7 | 8 | 9 | - |");
puts("|___|___|___|___|");
puts("|     0     | * |");
puts("|___________|___|");
}
 
 void face()
{
puts("___________________");
puts("|   XXXXXXXXXXX   |");
puts("|   ( ^     ^ )   |");
puts("|   ( 0     0 )   |");
puts("|    \\   |   /    |");
puts("|     \\     /     |");
puts("|      \\ = /      |");
puts("|       \\_/       |");
puts("|        |        |");
puts("|________|________|");
}
```
**OUTPUT**:IF YOU ENTER 0 THEN OUTPUT IS :
``` 
enter 0 to see a calculator or 1 to see face
0
 _______________
|               |
|_______________|
| 1 | 2 | 3 |   |
|___|___|___|   |
| 4 | 5 | 6 | + |
|___|___|___|___|
| 7 | 8 | 9 | - |
|___|___|___|___|
|     0     | * |
|___________|___|
```
IF YOU ENTER 1 THEN OUTPUT
```
enter 0 to see a calculator or 1 to see face
1
___________________
|   XXXXXXXXXXX   |
|   ( ^     ^ )   |
|   ( 0     0 )   |
|    \   |   /    |
|     \     /     |
|      \ = /      |
|       \_/       |
|        |        |
|________|________|
```
## 17:Write a program to check number is prime or not 
```
 #include<stdio.h>
int main()
{
 int a,i,p=0;
 printf("Enter the number");
 scanf("%d",&a);
 for(i=1;i<=a;i++)
{
 if(a%i==0)
  { 
    p++;
  }
}
 if(p==2)
 {
  printf("%d is prime number",a);
 } 
else{
printf("%d is not prime",a);
}
 
return 0;
}

```
**OUTPUT**:
```
Enter the number7
7 is prime number
```

## 18:Write a program to print range of prime numbers
 ```
 #include<stdio.h>
int main()
{
int a,b,i,n,p=0;
printf("Enter starting and ending number ");
scanf("%d%d",&a,&b);
for(i=a;i<=b;i++){
p=1;
for(n=2;n<i;n++)
{
if(i%n==0)
{
p=0;
break;
}
}
if(p==1){
printf ("%d is a prime number",i);
}
}
return 0;
}

```
**OUTPUT**:
```

Enter the starting and ending number 2 11
2 is a prime number3 is a prime number5 is a prime number7 is a prime number11 is a prime number
```

 ## 19:Write a program to show factorial result
 ```
#include<stdio.h>
int main()
{
 int a,result=1;
 printf("Enter the factorial of:");
 scanf("%d",&a);
 for(int i=a;i>=1;i--)
{
printf("%d X ",i);
result=result*i;
}
printf("= %d\n",result);
return 0;
}
```
**OUTPUT**:
```
Enter the factorial of:5
5 X 4 X 3 X 2 X 1 = 120
```
 ## 20:Write a program to find largest number from a matrix
 ```
 #include<stdio.h>
int main()
{
 
   int arr[50],size,i,large;
     printf("Enter size of array");
      scanf("%d",&size);
      printf("Enter the elements");
       for(i=0;i<size;i++)
           scanf("%d",&arr[i]);
         large=arr[0];
    for(i =0;i<size;i++)
     {
        if(large<arr[i])
           large=arr[i];
       }
printf("Largest element of %d",large);
return 0;
}
 ```
 **OUTPUT**:
 ```
 Enter size of array5
Enter the elements2 5 6 9 3
Largest element of 9
 ```
## 21:Write a program to show Matrix addition
 ```
   #include<stdio.h>
int main()
{
  int row,col,row1,col1,i,j;
   int arr[10][10],arr1[10][10],sum[10][10];
 printf("Enter the rows of 1 matrix");
 scanf("%d",&row);
 printf("Enter the columns of 1 matrix");
 scanf("%d",&col); 
 printf("Enter the elements of 1 matrix");
  for(i=0;i<row;i++)
   {
     for(j=0;j<col;j++)
        {
          scanf("%d",&arr[i][j]);
        }
   }
 printf("Enter the elements of 2 matrix");
 for(i=0;i<row;i++)
   {  
      for(j=0;j<col;j++)
        {
            scanf("%d",&arr1[i][j]);
       }
    }
for(i=0;i<row;i++)
{ 
   for(j=0;j<col;j++)
   {
      sum[i][j]= arr[i][j]+arr1[i][j];
     }
}
for(i=0;i<row;i++)
 { 
    for(j=0;j<col;j++)
     {
         printf("  %d",sum[i][j]);
           if(j==col-1)
                 printf("\n\n");
      }
 }
return 0;
}
 ```
 **OUTPUT**:
 ```
Enter the rows of 1 matrix2
Enter the columns of 1 matrix2
Enter the elements of 1 matrix3 1 4 2
Enter the elements of 2 matrix5 3 5 1

  8  4

  9  3
```
## 22:Write a program to show Matrix multipication
 ```
#include<stdio.h>
int main()
{
int sum=0,m,n,p,q,c,d,k;
int first[10][10], second[10][10], multiply[10][10];
// for matrix 1
printf("Enter the number of rows and column of first matrix:\n");
scanf("%d %d",&m,&n);
printf("Enter elements of first matrix:\n");

for(c=0;c<m;c++)
 for(d=0;d<n;d++)
  scanf("%d",&first[c][d]);
// for second matrix
printf("Enter the number of rows and columns of second matrix:\n");
scanf("%d %d",&p,&q);

if(n!=p){
printf("matrix multipication cannot be possible !!!!\n");}

else{
printf("Enter the elements of second matrix:\n");
for(c=0;c<p;c++)
 for(d=0;d<q;d++)
  scanf("%d",&second[c][d]);

for(c=0;c<m;c++)
{
 for(d=0;d<q;d++)
{
  for(k=0;k<p;k++)
{                             
  sum = sum + first[c][k] * second[k][d];
  }
   multiply[c][d] = sum;
 sum =0;
}
}

  printf("product of the matrix:\n");
  
  for(c=0;c<m;c++)
{
  for(d=0;d<q;d++)
   printf("%d\t",multiply[c][d]);
   printf("\n");
}
}                             
 return 0;
 }
 ```
 **OUTPUT**:
 ```
 Enter the number of rows and column of first matrix:
2 2
Enter elements of first matrix:
3 4
5 6
Enter the number of rows and columns of second matrix:
2 2
Enter the elements of second matrix:
1 2
3 4
product of the matrix:
15      22
23      34
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTk0Njc2OTc1MiwxNjU2OTAxNTI4LC03Mj
g2NzQ5NjUsLTc4ODExMDUzMywxNDAxMzg0NjY0LDE2MTgwMjUy
ODAsNDg3NDA0MzAxLDIwOTY4MjEwMzQsLTIxMjg5MTIwOTIsLT
I2MDQ0OTE2NywtMjc3NjA5ODExLDExMzUyMDA5NjEsLTY0MzA4
ODI1NiwzOTMzOTkyMzgsNzc0OTQ3NzEzLC0xOTM0OTcwMDY2LC
0xNTMzMjE1ODU2LDQwNzQ1NzQyMiwtMjMyMDc4MTA4LDEzMTEw
NDM5MzddfQ==
-->

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MzA1MDQxMjksMTk4NTg2OTYzMSwxOT
UwNjM2OTVdfQ==
-->
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTY1MzcwMTM5NV19
-->
