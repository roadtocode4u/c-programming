# Lecture-3 Rules to Declare Variables and Formatting Output

## Rules of Declare Variables

1. A Variable Name Can contain alphabates (A to Z)(a to z) , digits (0-9),underscore( _ ).

2. Cannot Start with digit.

3. Cannot use reserved keyword or special character.

4. Length of variable name should be less than 31 character.

## Case Sensitivity 

Text that is sensitive to capitalization of letters. For example, `NAME` ,`name`,`NaMe` are three different.

**Example : Write a program to sum of 2 variable**

```c
#include <stdio.h>

int main() {
    int a=10;
    int b=20;
    int c;
    
    c=a+b;
    
    printf("%d",c);
    
    return 0;
}
```

**⚙️ Output :**
>30

**💻Example :**
```c
#include <stdio.h>

int main() {
    int val1=30;
    int val2=20;
    int sum;
    
    sum=val1 + val2;
    
    printf("%d",sum);
    
    return 0;
}
```
**⚙️ Output :**
>50

**💻Example :**
```c
#include <stdio.h>

int main() {
    int val1=30, val2=20, sum;
    
    sum=val1 + val2;
    
    printf("%d",sum);
    
    return 0;
}
```
**⚙️ Output :**
>50 

## Formatting Output

**💻Example :**
```c
#include <stdio.h>

int main() {
    int val1=30, val2=20, sum;
    
    sum=val1 + val2;
    
    printf(" sum = %d",sum);
    
    return 0;
}
```
**⚙️ Output :**
>sum = 50 

**💻Example :**
```c
#include <stdio.h>

int main() {
    float num = 20.5;
    
    printf("Numberis %f", num);
    
    return 0;
}
```
**⚙️ Output :**
>Numberis 20.500000

**💻Example :**
```c
#include <stdio.h>

int main()
{
    float weight=80.5;
    
    printf("%f",weight);
    
    return 0;
}
```
**⚙️ Output :**
>80.500000

**💻Example :**
```c
#include <stdio.h>

int main() {
    int a = 10;
    int b = 20;
    int c = a + b;
    
    printf("a=%d b=%d",a,b);
    
    return 0;
}
```
**⚙️ Output :**
>a=10 b=20

**💻Example :**
```c
#include <stdio.h>

int main() {
    int val1 = 10;
    int val2 = 20;
    int sum = val1 + val2;
    
    printf("sum of %d and %d is %d",val1,val2,sum);
    
    return 0;
}
```
**⚙️ Output :**
>sum of 10 and 20 is 30
## 🔗 Some Useful Links

## 📖 References
