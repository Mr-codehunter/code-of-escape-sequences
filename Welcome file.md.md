**Codes of Escape Sequence**


**1. sum of two numbers**
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
**2. Find Out the Reamainder** 
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
**3. Find Out the Average**
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
**4. multiply using \t**
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
   **5. Print ASCII value**
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
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTM3NzAwNDczLDYxODMyNTA5MywxMDE3ND
gyMTQ3LC0zNzAyMjgzOSwtMjQ3NzQyODAzLDM2NTE3MzQzNiwt
MTA2MDI0MjQ4NSwxMzIzMzkwMTA5LDE5NDAwMjExNjEsLTE3ND
k1MTQ2NSw5MTY5ODU2ODBdfQ==
-->