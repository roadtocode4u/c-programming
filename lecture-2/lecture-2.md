# Lecture-2 Datatype, Variables and Format Specifiers

## New Line Charachter

`\n` is used to New line Character.

**Example :**
```c
#include <stdio.h>

int main() {
  
    printf("Good Morning !\n");
    printf("Good afternoon !");
    
    return 0;
}

```

**⚙️ Output :**
>Good Morning !     
Good afternoon !

## String :

Strings is represented as Collection of characters.

## Variable :

Variable is used to store data.

## Datatype :

**1. Integers (int)**

 Intergers means Stores whole numbers without decimals point.

💻Example  =1,2,2253,899,44,55...

**2. Character (char)**

Stores a single character,letter.

💻Example='r','v','s'....

**3. Float (float)**

float means Stores numbers with decimals point.

💻Example= 15.7,89.0,46.84 ....

## Format Specifiers:
 
 There are different format specifiers for each data type.

`%d`=int

`%f`=float

`%c`=char

**💻Example :**
```c
#include <stdio.h>

int main()
 {
  
   int age=10;
   
   printf("%d",age);
    
    return 0;
}
```
**⚙️ Output :**
>10 

**💻Example :**
```c
#include <stdio.h>

int main()
{
    
   int age;
   age=30;
   
   printf("%d",age);
    
    return 0;
}
```
**⚙️ Output :**
>30 

**💻Example :**
```c
#include <stdio.h>

int main()
{
    
   int age;
   age=30;
   age=50;
   
   printf("%d",age);
    
    return 0;
}
```
**⚙️ Output :**
>50 

**💻Example :**
```c
#include <stdio.h>

int main()
{
    
   int age;
   age=30;
   printf("%d",age);
   
   age=50;
   printf("%d",age);
    
    return 0;
}
```
**⚙️ Output :**
>3050 

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

int main()
{
    char alpha='c';
    
    printf("%c",alpha);
    
    return 0;
}
```
**⚙️ Output :**
>c
## 🔗 Some Useful Links

## 📖 References
