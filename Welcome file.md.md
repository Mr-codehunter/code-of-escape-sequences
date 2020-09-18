**Codes of Escape Sequence**


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
**2. Find Out the Remainder using \t** 
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
**3. Find Out the Average using \n**
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
**4. Print Something using \t**
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
**5. multiply using \t**
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
**8. Print Something using \b**
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
**9. write a program to print your name using \b**
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
**12. write a program using \r**
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
**17. Write a program to using \\'**
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbNzk3MTgwMDE3LDE0NTYwMDY5ODEsLTIwNT
kwMjU5MjcsMTA4MzQzNTIyNCw1MTY5NjI3NTgsNTUxNTQ1NzA4
LC0xMzMyOTY5NTE5LDEwOTE3NTEzOCwyMDQ3MTQyMTU0LC05Mj
kwNTU4MzUsMTE2NTA5ODEwMiwxMzI1MTk3NzYxLDE5MzI1MTY4
NzMsMTM3NzAwNDczLDYxODMyNTA5MywxMDE3NDgyMTQ3LC0zNz
AyMjgzOSwtMjQ3NzQyODAzLDM2NTE3MzQzNiwtMTA2MDI0MjQ4
NV19
-->