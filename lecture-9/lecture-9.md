# Lecture-8 Logical Operators C Programming 

## Logical Operators 

Logical operator are used to chaining condition.

* Logical AND (&&)
* Logical OR (||)
* Logical Not (!)

### Logical AND (&&) 
  
  Result True, if both operand condition are true otherwise false.

**💻Example:**
```c

#include <stdio.h>

int main() {
 int physics=95;
 int maths=98;
 
   if (physics>=80 && maths>=80)
 {
     printf("Admmision Granted ...");
 }
 else
 {
     printf("Admmision Rejected ...");
 }
    
    return 0;
}
```
**⚙️ Output :**
>Admmision Granted ..

**💻Example:**
```c

#include <stdio.h>

int main() {
 int physics=50;
 int maths=98;
 
   if (physics>=80 && maths>=80)
 {
     printf("Admmision Granted ...");
 }
 else
 {
     printf("Admmision Rejected ...");
 }
    
    return 0;
}
```
**⚙️ Output :**
>Admmision Rejected ...

**💻Example:**
```c

#include <stdio.h>

int main() {
 int physics=95;
 int maths=45;
 
   if (physics>=80 && maths>=80)
 {
     printf("Admmision Granted ...");
 }
 else
 {
     printf("Admmision Rejected ...");
 }
    
    return 0;
}
```
**⚙️ Output :**
>Admmision Rejected ...

 ###  Logical OR (||)

 Result True if both operand condition are true and one of the condition is true otherwise result False.

**💻Example:**
```c
#include <stdio.h>

int main()
{
 int physics=90;
 int maths=98;
 
   if (physics>=80 || maths>=80)
 {
     printf("Admmision Granted ...");
 }
 else
 {
     printf("Admmision Rejected ...");
 }
    
    return 0;
}
```
**⚙️ Output :**
>Admmision Granted ...

**💻Example:**
```c

#include <stdio.h>

int main()
{
 int physics=0;
 int maths=98;
 
   if (physics>=80 || maths>=80)
 {
     printf("Admmision Granted ...");
 }
 else
 {
     printf("Admmision Rejected ...");
 }
    
    return 0;
}
```
**⚙️ Output :**
>Admmision Granted ...

**💻Example:**
```c
#include <stdio.h>

int main()
{
 int physics=90;
 int maths=0;
 
   if (physics>=80 || maths>=80)
 {
     printf("Admmision Granted ...");
 }
 else
 {
     printf("Admmision Rejected ...");
 }
    
    return 0;
}
```
**⚙️ Output :**
>Admmision Granted ...
 
**💻Example:**
```c
#include <stdio.h>

int main()
{
 int physics=0;
 int maths=0;
 
   if (physics>=80 || maths>=80)
 {
     printf("Admmision Granted ...");
 }
 else
 {
     printf("Admmision Rejected ...");
 }
    
    return 0;
}
```
**⚙️ Output :**
>Admmision Rejected ...


### Logical Not (!)

**💻Example:**
```c
#include <stdio.h>

int main() 
{
    
    int physics=70;
   
    
    int result=!(physics>=80);
    printf("Result=%d",result);
    
    return 0;
}
```
**⚙️ Output :**
>Result=1


## 🔗 Some Useful Links

## 📖 References