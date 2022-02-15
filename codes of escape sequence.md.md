

## *Codes of Escape Sequences*



**1. sum of two numbers using \n**
```
#include<iostream>
using namespace std;
int main()
{
int a,b,sum;
cout<<"Enter the value of a :\n";
cin>>a;
cout<<"Enter the value of b:\n";
cin>>b;
sum=a+b;
cout<<"The sum of a and b is :\n"<<sum;
return 0;
}
```

**Output :**
```
Enter the value of a :
45
Enter the value of b:
45
The sum of a and b is :
90
```
**2. Find out the remainder using \n** 
```
#include<iostream>
using namespace std;
int main()
{
float a,b,remainder;
cout<<"Enter first number :\n";
cin>>a;
cout<<"Enter second number :\n";
cin>>b;
remainder=a/b;
cout<<"The remainder of a and b is :\n"<<remainder;
return 0;
}
```
**Output :**
```
Enter first number :
70
Enter second number :
15
The remainder of a and b is :
4.66667
```
**3. Find out the average using \n**
```
#include<iostream>
using namespace std;
int main()
{
float a,b,sum,average;
cout<<"Enter first number :\n";
cin>>a;
cout<<"Enter second number :\n";
cin>>b;
sum=a+b;
average=sum/2;
cout<<"The sum of a and b is :\n"<<sum<<"\n";
cout<<"The average of a and b is :\n"<<average;
return 0;
}
```
**Output :**
```
Enter first number :
78
Enter second number :
45
The sum of a and b is :
123
The average of a and b is :
61.5
```
**4. Print something using \t**
```
#include<iostream>
using  namespace  std;
int  main()
{
cout<<"MY name is Deepak.\tI am 19 Years old.\t";
cout<<"I want to become an hacker.\tI am a Btech student.";
return 0;

}
```
**Output :**
```
MY name is Deepak.      I am 19 Years old.      I want to become an hacker.     I am a Btech student.
```
**5. Write a program to multiply using \t**
```
#include<iostream>
using  namespace  std;
int  main()
{
int  a, b, mly;
cout<<"\tEnter\t first\t number\t:\t";
cin>>a;
cout<<"\tEnter \tsecond \tnumber\t:\t";
cin>>b;
mly=a*b;
cout<<"\tThe \tmultiplication \tof \ta \tand \tb \tis \t:\t"<<mly<<"\t";
return  0;
}
```
**Output :**
```
        Enter    first   number :       45
        Enter   second  number  :       45
        The     multiplication  of      a       and     b       is      :       2025
   ```
   **6. Print ASCII value using \t**
   ```
   #include<iostream>
using  namespace  std;
int  main()
{
char  c;
cout<<"\tEnter \ta \tcharcter \t:\t";
cin>>c;
cout<<"\tASCII \tvalue \tof\t "<<c<<"\tis\t"<<int(c)<<"\t";
return 0;
}
```
**Output :**
```
        Enter   a       charcter        :       x
        ASCII   value   of       x      is      120
```
**7. Division of numbers using \b**
```
#include<iostream>
using  namespace  std;
int  main()
{
float  num1,num2,div;
cout<<"\bEnter\b  \bthe\b  \bvalues\b of\b two\b numbers\b\b";
cin>>num1;
cin>>num2;
div=num1/num2;
cout<<"\bThe\b value\b is\b :\b "<<div<<"\b";
return  0;
}
```
**Output :**
```
Entethvalue o tw numbe145
2
Th valu i  72.5
```
**8. Print something using \b**
```
#include<iostream>
using  namespace  std;
int  main()
{
cout<<"\bPM \bNarendra Modi\b announces\b panel\b to study \b\b\bjoint polls\b\b";
cout<<"The \b\bPrime Minister\b\b\b\b of India is Narendra\b\b\b\b Modi";
return  0;
}
```
**Output :**
```
PMNarendra Mod announce pane to stujoint polThPrime Mini of India is Nare Modi
```
**9. Write a program to print your name using \b**
```
#include<iostream>
using  namespace  std;
int  main()
{
int  i;
for (i=1; i<=20; ++i)
{
cout<<"My Namesssss\b\b\b\b\b is Deepak Kumarrrr\b\b\b. I am 19 Yearss\b old.\n\n";
}
return  0;
}
```
**Output :**
```
My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.

My Name is Deepak Kumar. I am 19 Years old.
```

**10. Write a program using \r**
```
#include<iostream>
using  namespace  std;
int  main()
{
int  a=2;
double  const  b=4;
float  c=105;
char  d='A';
cout<<"The value of a is : "<<a;
cout<<"The \rvalue of b is\r : "<<b;
cout<<"The value \rof c \ris : "<<c;
cout<<"The value of d is : "<<d;
return  0;
}
```
**Output :**
```
is : 105The value of d is : A
```
**11. Write  a program using \r**
```
#include<iostream>
using  namespace  std;
int  main()
{
int  num;
cout<<"\rEnter an Number. It is a even number\r :";
cin>>num;
return  0;
}
```
**Output :**
```
:40r an Number. It is a even number
```
**12. Write a program using \r**
```
#include<iostream>
using  namespace  std;
int  main()
{
int  num;
cout<<"\rEnter an Number : ";
cin>>num;
if(num<=9)
cout<<"It is an interger number\r :";
else
{
cout<<"It is not an integer \rnumber :";
}
return  0;
}
```
**Output :**
```
Enter an Number : 9
 : is an interger number
 
 Enter an Number : 15
number :t an integer
```
**13. Write a program using \\\\**
```
#include<iostream>
using  namespace  std;
int  main()
{
cout<<"He\\she is an great programmer in c\\c++\\java\\javascript\\python\\.";
return  0;
}
```
**Output :**
```
He\she is an great programmer in c\c++\java\javascript\python\.
```
**14. Write a program using \\\\**
```
#include  <iostream>
using  namespace  std;
int  main()
{
int  rows;
cout  <<  "Enter number of rows: ";
cin  >>rows;
for(int  i = 1; i <= rows; ++i)
{
for(int  j = 1; j <= i; ++j)
{
cout  <<  "\\He\\She is a good programmer\\Hacker\\Teacher. ";
}
cout  <<  "\n";
}
return  0;
}
```
**Output :**
```
\He\She is a good programmer\Hacker\Teacher.
\He\She is a good programmer\Hacker\Teacher. \He\She is a good programmer\Hacker\Teacher.
\He\She is a good programmer\Hacker\Teacher. \He\She is a good programmer\Hacker\Teacher. \He\She is a good programmer\Hacker\Teacher.
\He\She is a good programmer\Hacker\Teacher. \He\She is a good programmer\Hacker\Teacher. \He\She is a good programmer\Hacker\Teacher. \He\She is a good programmer\Hacker\Teacher.
```
**15. write a program using \\\\**
```
#include<iostream>
using  namespace  std;
int  main()
{
int  age;
cout<<"Enter the age : ";
cin>>age;
if(age>18)
{
cout<<"He\\She can vote in India.\n";
}
else  if (age<18)
{
cout<<"He\\She cannot vote in India.\n";
}
else 
{
cout<<"you entered 18."<<endl;
}
cout<<"This is a vote program.\n";
return  0;
}
```
**Output :**
```
Enter the age : 12
He\She cannot vote in India.
This is a vote program.

Enter the age : 45
He\She can vote in India.
This is a vote program.

Enter the age : 18
you entered 18.
This is a vote program.
```
**16. Print Hello Brother using \\'**
```
#include<iostream>
using  namespace  std;
int  main()
{
int  i;
for (i=1; i<=5; ++i)
cout<<"\'Hello Brother  "<<"!\n";
return 0;
}
```
**Output :**
```
'Hello Brother  !
'Hello Brother  !
'Hello Brother  !
'Hello Brother  !
'Hello Brother  !
```
**17. Write a program to find leap year \\'**
```
#include  <iostream>
using  namespace  std;
int  main()
{
int  year;
cout  <<  "\'Enter a year: "<<"\'";
cin  >>  year;
if (year % 4 == 0)
{
if (year % 100 == 0)
{
if (year % 400 == 0)
cout  <<  year  <<  " \'is a leap year\'.";
else
cout  <<  year  <<  " \'is not a leap year\'.";
}
else
cout  <<  year  <<  " \'is a leap year.\'";
}
else
cout  <<  year  <<  " \'is not a leap year.\'";
return  0;
}
```
**Output :**
```
'Enter a year: '1947
1947 'is not a leap year.'

'Enter a year: '2020
2020 'is a leap year.'
```
**18. Write a Program to Print any Table using \\'**
```
#include  <iostream>
using  namespace  std;
int  main()
{
int  n;
cout  <<  "\'Enter an integer: \'";
cin  >>  n;
for (int  i = 1; i <= 10; ++i) {
cout  <<"\'"<<  n  <<  " * "  <<  i  <<  " = "  <<"\'"<<n * i<<"\n" ;
}
return  0;
}
```
**Output :**
```
'Enter an integer: '79
'79 * 1 = '79
'79 * 2 = '158
'79 * 3 = '237
'79 * 4 = '316
'79 * 5 = '395
'79 * 6 = '474
'79 * 7 = '553
'79 * 8 = '632
'79 * 9 = '711
'79 * 10 = '790
```
**19. Write a Program to find out the Factorial using \\"**
```
#include  <iostream>
using  namespace  std;
int  main()
{
unsigned  int  n;
unsigned  long  long  factorial = 1;
cout  <<  "\"Enter a positive integer: \"";
cin  >>  n;
for(int  i = 1; i <=n; ++i)
{
factorial *= i;
}
cout  <<  "\"Factorial of "  <<  n  <<  " = "  <<  factorial<<"\"";
return  0;
}
```
**Output :**
```
"Enter a positive integer: "45
"Factorial of 45 = 9649395409222631424"
```
**20. Write a program to swap of two numbers using \\"**
```
#include  <iostream>
using  namespace  std;
int  main()
{
int  a = 5, b = 10, temp;
cout  <<  "\"Before swapping.\""  <<  endl;
cout  <<"\n""\"a = "  <<  a  <<  ", b = \""  <<  b  <<  endl;
temp = a;
a = b;
b = temp;
cout  <<  "\n\"After swapping.\""  <<  endl;
cout  <<"\n""\"a = "  <<  a  <<  ", \"b = "  <<  b  <<  endl;
return  0;
}
```
**Output :**
```
"Before swapping."

"a = 5, b = "10

"After swapping."

"a = 10, "b = 5
```
**21. Write a program to print something using \\"**
```
"Follow me on  my "GITHUB" Account @ "Mr-codehunter" and if u contact me please send an "E-mail on : "Writtten Soon" and my "contact no. is "8847547031"
"Follow me on  my "GITHUB" Account @ "Mr-codehunter" and if u contact me please send an "E-mail on : "Writtten Soon" and my "contact no. is "8847547031"
"Follow me on  my "GITHUB" Account @ "Mr-codehunter" and if u contact me please send an "E-mail on : "Writtten Soon" and my "contact no. is "8847547031"
"Follow me on  my "GITHUB" Account @ "Mr-codehunter" and if u contact me please send an "E-mail on : "Writtten Soon" and my "contact no. is "8847547031"
"Follow me on  my "GITHUB" Account @ "Mr-codehunter" and if u contact me please send an "E-mail on : "Writtten Soon" and my "contact no. is "8847547031"
```


## *Thanks a lot for Visiting and watching..... my codes and if any quires and any mistakes in my program please u can ask me,...on contact :8847547031*

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQxOTcwNTI1NSwyNDkyOTg1MzQsMTk5Nz
A0NDM4NF19
-->
