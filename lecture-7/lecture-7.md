# Lecture-6  Assignment Operators, Comparison Operators and  Ternary Operator in C Programming 

## Assignment operators

Assignment operators applied to assign the result of an expression to a variable.

### Assign (=)

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int a = 10;
    
    printf("%d",a);
    
    return 0;
}
```
**⚙️ Output :**
>10

 ### Add then assign (+=)

**💻Example:**
```c

#include <stdio.h>

int main() {
    
    int a =5;
    
    a += 3; //a = a + 3;
    
    printf("%d",a);
    
    return 0;
}
```
**⚙️ Output :**
>8

 ### Substract then assign (-=)
 
**💻Example:**
```c

#include <stdio.h>

int main() {
    
    int a =5;
    
    a -= 3; //a = a - 3;
    
    printf("%d",a);
    
    return 0;
}
```
**⚙️ Output :**
>2

### Multiplies then assign (*=)
 
**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int a =5;
    
    a *= 3; //a = a * 3;
    
    printf("%d",a);
    
    return 0;
}
```
**⚙️ Output :**
>15

### Divides then assign(/=)
 
**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int a =10;
    
    a /= 2; //a = a / 2;
    
    printf("%d",a);
    
    return 0;
}
```
**⚙️ Output :**
>5

### Modulus then assign(%=)
 
**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int a =7;
    
    a %= 2; //a = a % 2;
    
    printf("%d",a);
    
    return 0;
}
```
**⚙️ Output :**
>1

## Comparison Operators 

### Equal to (==)

Equal to are used to compare to object. 

**💻Example:**
```c
// if value are not equal then print 0 means false.
#include <stdio.h>

int main() {
    
    int a = 5;
    int b = 10;
    
    int ans = (a==b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>0 

**💻Example:**
```c
// if value are equal then print 1 means true.
#include <stdio.h>

int main() {
    
    int a = 10;
    int b = 10;
    
    int ans = (a==b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>1 

### Greater than (>)

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int a = 5;
    int b = 10;
    
    int ans = (a>b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>0 

**💻Example:**
```c
//a is greater than b then true.
#include <stdio.h>

int main() {
    
    int a = 5;
    int b = 2;
    
    int ans = (a>b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>1

### Less than (<)

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int a = 20;
    int b = 10;
    
    int ans = (a<b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>0 

**💻Example:**
```c
// a is less than b then true .
#include <stdio.h>

int main() {
    
    int a = 10;
    int b = 20;
    
    int ans = (a,b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>1

### Less than or equal to (<=)

**💻Example:**
```c
// a is less than or equal to b then true otherwise false.
#include <stdio.h>

int main() {
    
    int a = 100;
    int b = 10;
    
    int ans = (a<=b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>0 

**💻Example:**
```c
// a is less than or equal to b then true.
#include <stdio.h>

int main() {
    
    int a = 10;
    int b = 10;
    
    int ans = (a<=b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>1

### greater  than or equal to (>=)

**💻Example:**
```c
// a is greater  than or equal to b then true otherwise false.
#include <stdio.h>

int main() {
    
    int a = 1;
    int b = 10;
    
    int ans = (a<=b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>0 

**💻Example:**
```c
// a is greater than or equal to b then true.
#include <stdio.h>

int main() {
    
    int a = 100;
    int b = 10;
    
    int ans = (a<=b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>1

###	not equal to (!=)

**💻Example:**
```c
//a is not equal to b then true otherwise false.
#include <stdio.h>

int main() {
    
    int a = 10;
    int b = 10;
    
    int ans = (a!=b);
    
    printf("%d",ans);
    
    return 0;

```
**⚙️ Output :**
>0 

**💻Example:**
```c
//a is not equal to b then true.
#include <stdio.h>

int main() {
    
    int a = 20;
    int b = 10;
    
    int ans = (a!=b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>1

## Ternary Operator 

**Syntax :**
```c
(condition)?True:False
```

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int a = 100;
    int b = 10;
    
    int ans = (a>b?a:b);
    
    printf("%d",ans);
    
    return 0;
}
```
**⚙️ Output :**
>100

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int num;
    printf("Enter Number :");
    scanf("%d",&num);
    
    int ans = (num%2==0)?printf("Even"):printf("odd");
    
    return 0;
}
```
**⚙️ Output :**
>Even

## 🏠Homework 

>1️⃣ Write a program to take age from user and check if he / she eligible for voting.


## 🔗 Some Useful Links

## 📖 References