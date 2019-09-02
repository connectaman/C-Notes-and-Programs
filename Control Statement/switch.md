### C++ switch

-----

The C++ switch statement executes one statement from multiple conditions. It is like if-else-if ladder statement in C++.

```objectivec
switch(expression){      
case value1:      
 //code to be executed;      
 break;    
case value2:      
 //code to be executed;      
 break;    
......      
      
default:       
 //code to be executed if all cases are not matched;      
 break;    
} 
```

![](https://static.javatpoint.com/cpp/images/cpp-switch1.png)

Example
```objectivec
#include <iostream>  
using namespace std;  
int main () {  
       int num;  
       cout<<"Enter a number to check grade:";    
       cin>>num;  
           switch (num)    
          {    
              case 10: cout<<"It is 10"; break;    
              case 20: cout<<"It is 20"; break;    
              case 30: cout<<"It is 30"; break;    
              default: cout<<"Not 10, 20 or 30"; break;    
          }    
    } 
```
Ouput
```
Enter a number:
10
It is 10
```
