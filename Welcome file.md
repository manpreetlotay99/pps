 
<center><img src="https://i.imgur.com/EZtECRw.png"></center>

---

<h3><b>Guru Nanak Dev Engineering College
    ESC-18104/18105 Programming for Problem Solving</b>
  
  
     
    Name-Manpreet kaur
    Branch-InformationTechnology
    Section - A2 
    Roll Number - 1921062
    
    # My C programes 

## 1:To print hello world

```
//To print  hello world
#include<stdio.h>
int main()
{                     
 printf("\nHello world\n");
}
```
**OUTPUT:**
``` 
 Hello world
```
## 2:To fill your information

```
  // To fill your information
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
Name = Jony

Roll no=100012

Age = 25

Phone no.= 9922115566

The name is Jony
Your roll no is 100012
My phone number is 9922115566
 My age is 25
 ```

## 3:To find sum of two numbers
```

     // to find sum of two numbers
     #include<stdio.h>
int main()
{                                                                                      
 int a;
 int b;
 int c ;
 printf("Enter two numbers to get sum:");
 scanf("%d  %d",&a,&b);
 printf(" \nThe result is :%d + %d= %d\n",a,b,c=a+b);
    return 0;
 }
```
**OUTPUT**:
```
Enter two numbers to get sum:45 55
 
The result is :45 + 55= 100
```
## 4:Sum and average of numbers
```
 // sum and average of number
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
  ## 5:To find number is even or odd
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
Enter a number:4
The  number is even
```
***OR***
```
Enter a number:7
The number is odd
```
## 6:To show the size of int,float,char,double,long,short
```
 // size of int, float, char, double, long, short
#include<stdio.h>
int main()
{                                   
 printf("Integer:%d\n",sizeof(int));
 printf("float:%d\n",sizeof(float));
 printf("character:%d\n",sizeof(char));
 printf("double:%d\n",sizeof(double));
 printf("short:%d\n",sizeof(short));
 printf("long:%d\n",sizeof(long));
 }
```
**OUTPUT**:
```
Integer:4
float:4
character:1
double:8
short:2
long:8
```
## 7:To show area,perimeter,volume of square
```
   
 //Area,premiter,volume of square
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
Enter the side of square:4

Perimeter of square:16
Area of square:16
Volume of square:64
```
## 8:To show puts value upto n number using loop
```
// to show punishment using loop
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
## 9:To show area,diameter,circumference of circle 
```
   #include<stdio.h>
 int main()
  {
    float a;   
float  const pi=3.14;
   printf("Enter radius of circle:");
    scanf("%f\n",&a);
  printf("diameter of circle is:%f\n",2*a);
  printf("circumference of circle:%f\n",2*pi*a);
  printf("Area of circle:%f\n",pi*a*a);
return 0;
 } 
```
**OUTPUT**:
```
Enter radius of circle:6
diameter of circle is:12.000000
circumference of circle:37.680000
Area of circle:113.040001
```
## 10:To find area and volume of rectangle
```
//find area and volume of rectangle
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
 Enter length of rectangle:4 

Enter breadth of rectangle:3 

Enter height of rectangle:4

The area of rectangle is:12
The volume is :48
```
 
 ##  11 .To represent a table of user input 
 
 ```
  // To represent a table of user input  number
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
## 12:To convert Fahrehnite to Celcius
```
//to convert fahrehnite to celcius
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
## 13: To show the table range 
```
//To show a range of table upto user input
#include<stdio.h>
int main()
{
 int a,b,n;
 printf("table of:");
 scanf("%d",&a);
 printf("\n enter the starting value of range:");
 scanf("%d",&b);
 printf("\n enter the last value of range:");
 scanf("%d",&n);
 for(b;b<=n;b++)
 printf("%d x %d = %d\n",a,b,a*b);
 return 0;
 }
```
**OUTPUT**:
```
table of:5

 enter the starting value of range:20

 enter the last value of range:30
5 x 20 = 100
5 x 21 = 105
5 x 22 = 110
5 x 23 = 115
5 x 24 = 120
5 x 25 = 125
5 x 26 = 130
5 x 27 = 135
5 x 28 = 140
5 x 29 = 145
5 x 30 = 150
```
## 14:To show even table
```
//To show only even table
#include<stdio.h>
int main(){
int m;
printf("tabel of:");
scanf("%d",&m);
if(m%2==0)
{
for(int i=0;i<=20;i++)
{
printf("%d X %d=%d\n",m,i,m*i);
}}
else
printf("enter even number\n");

return 0;}
```
**OUTPUT**:
```
tabel of:16
16 X 0=0
16 X 1=16
16 X 2=32
16 X 3=48
16 X 4=64
16 X 5=80
16 X 6=96
16 X 7=112
16 X 8=128
16 X 9=144
16 X 10=160
16 X 11=176
16 X 12=192
16 X 13=208
16 X 14=224
16 X 15=240
16 X 16=256
16 X 17=272
16 X 18=288
16 X 19=304
16 X 20=320
```
## 15: To show result of operands
```
//To show results using operands(+,-,*,%,/)
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
enter first  number:20
enter operator[+ - % / *]: *
enter second number:10
The result is:200.00
```
## 16:To call a patterns of face and calculator
```
// call a pattern of face or calculator
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
## 17:To convert fahrehnite to celcius and kelvin
```
  // To covert  fahrenheit to celsius and kelvin
                 #include<stdio.h>
 int main()
 {
  float a,b,c;
  printf("Enter a fahrenheit value:");
  scanf("%f",&a);
b=((a-32.00)*5.00)/9.00;
 printf("celsius value is:%.2f\n",b);

 printf("kelvin value is:%.2f\n",c=b+273.15);
  return 0;} 
```
**OUTPUT**:
```
Enter a fahrenheit value:450
celsius value is:232.22
kelvin value is:505.37
```

## 18:To show stars pattern
```
 // TO show stars using loop 
#include<stdio.h>
int main()
{ int i,j,k;
 printf("Enter the no. to show pattern:");
 scanf("%d",&k);
 
  for(i=k;i>=1;i--)
 {
  for(j=i;j>=1;j--)
 {
  printf("* ");
 }
 printf("\n");
 }
 return 0;
 }
 ```
 **OUTPUT**:
 ```
 Enter the no. to show pattern:8
* * * * * * * * 
* * * * * * * 
* * * * * * 
* * * * * 
* * * * 
* * * 
* * 
*
```
 
 ## 19:To show factorial result
 ```
 //To show factorial of user input
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
5 X 4 X 3 X 2 X 1 X = 120
```
 ## 20:To show stars pattern 
 ```
 //to show star pattern for n numbers
#include<stdio.h>
int main()
{
 int i,j,k;
 printf("Enter the value upto pattern is shown:");
 scanf("%d",&k);

 for(i=1;i<=k;i++)
{
  for(j=1;j<=i;j++)
{
  printf("* ");
 }
 printf("\n");
 }
 return 0;
}
```
**OUTPUT**:
```
Enter the value upto pattern is shown:8
* 
* * 
* * * 
* * * * 
* * * * * 
* * * * * * 
* * * * * * * 
* * * * * * * * 
```

## 21:Matrix multipication
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