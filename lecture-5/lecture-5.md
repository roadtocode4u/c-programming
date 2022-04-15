# Lecture-5 Increment, Decrement Operator and Scanf Functions in C Programming 

**💻Example:**
```c
#include <stdio.h>

int main() {
   
   int count=5;
   
   count=count + 1;
   
    printf("%d",count);
    
    return 0;
}
```
**⚙️ Output :**
>6

* value Increase 

**💻Example:**
```c
#include <stdio.h>

int main() {
   
   int count=5;
   //count => 5
   printf("\n%d",count);
   
   count=count + 1;
   //count => 6
   printf("\n%d",count);
    
    count=count + 1;
    //count => 7
    printf("\n%d",count);
    return 0;
}
```
**⚙️ Output :**
>5   
6   
7


* value Decrease

**💻Example:**
```c

#include <stdio.h>

int main() {
   
   int count=5;
   //count => 5
   printf("\n%d",count);
   
   count=count - 1;
   //count => 4
   printf("\n%d",count);
    
    count=count - 1;
    //count => 3
    printf("\n%d",count);
    return 0;
}
```
**⚙️ Output :**
>5     
4    
3  

## Increment Operator (++)

This Operator are used to increase the value of variable.

By Defalut, the value is incremented by **1**.

**💻Example:**
```c

#include <stdio.h>

int main() {
   
   int count=5;
   //count => 5
   printf("\n%d",count);
   
   count++;
   //count => 6
   printf("\n%d",count);
    
    count++;
    //count => 7
    printf("\n%d",count);
    return 0;
}
```
**⚙️ Output :**
>5  
6     
7

**💻Example:**
```c

#include <stdio.h>

int main() {
   
   int count=5;
   count =count+2;
    printf("\n%d",count);
    return 0;
}
```
**⚙️ Output :**
>7

## Type of Increment Operator

1. Pre-Increment (++var)
2. Post-Increment (var++)

**💻Example:**
```c
#include <stdio.h>

int main() {
   
   int val1 = 0;
   val1++; //Post Increment 
   printf("\n%d",val1);
   
   
   int val2 = 0;
   ++val2; //Pre Increment 
   printf("\n%d",val2);
   
    return 0;
}
```
**⚙️ Output :**
>1  
1

**💻Example:**
```c
#include <stdio.h>

int main() {
   
   int val1 = 0;
   
   int result = val1++;
   
   printf("\n%d",result);

   printf("\n%d",val1);
    return 0;
}
```
**⚙️ Output :**
>0    
1 

**💻Example:**
```c
#include <stdio.h>

int main() {
   
   int val1 = 0;
   
   int result = ++val1;
   
   printf("\n%d",result);
   
   printf("\n%d",val1);
    return 0;
}
```
**⚙️ Output :**
>1    
1

## Decrement Operator (++)

This Operator are used to decrease the value of variable.

By Defalut, the value is Decremented by **1**.

**💻Example:**
```c


#include <stdio.h>

int main() {
   
   int count=5;
   //count => 5
   printf("\n%d",count);
   
   count--;
   //count => 4
   printf("\n%d",count);
    
    count--;
    //count => 3
    printf("\n%d",count);
    return 0;
}
```
**⚙️ Output :**
>5   
4    
3


**💻Example:**
```c
#include <stdio.h>

int main() {
   
   int count=5;
   count--;
   count--;
   count--;
    printf("\n%d",count);
    return 0;
}
```
**⚙️ Output :**
>2

## Type of Decrement Operator

1. Pre-Decrement (--var)
2. Post-Decrement (var--)

**💻Example:**
```c

#include <stdio.h>

int main() {
   
   int val1 = 5;
   
   int result = val1--;
   
   printf("\n%d",result);
   
   printf("\n%d",val1);
    return 0;
}
```
**⚙️ Output :**
>5   
 4  

 **💻Example:**
```c
#include <stdio.h>

int main() {
   
   int val1 = 5;
   
   int result = --val1;
   
   printf("\n%d",result);
   
   printf("\n%d",val1);
    return 0;
}
```
**⚙️ Output :**
>4      
4  

## scanf() function:

The scanf() function which is used for input, to  read the input data from the console.

 **💻Example:**
```c
#include <stdio.h>

int main() {
    
    int val;
    
    printf("Enter value of val:");
    scanf("%d",&val);
    
    printf("output is %d",val);
 
    return 0;
}
```
**⚙️ Output :**
>Enter value of val:10    
output is 10  

 **💻Example:**
```c
#include <stdio.h>

int main() {
    
     int num1;
     int num2;
     int sum;
     
     printf("Enter Value of num1 :");
     scanf("%d",&num1);
     
     printf("Enter Value of num2 :");
     scanf("%d",&num2);
     
     sum = num1 + num2;
     
     printf("sum:%d",sum);
 
    return 0;
}
```
**⚙️ Output :**
>Enter Value of num1 :10   
Enter Value of num2 :20    
sum:30   
## 🔗 Some Useful Links

## 📖 References