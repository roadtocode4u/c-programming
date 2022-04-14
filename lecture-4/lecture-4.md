# Lecture-4 Operators and Comments in C Programming 

## Operators 

Operators are used to perform operations on variables and values.

**Types of Operators =**
* Arithmetic operators (+,-,*,/,%)
* Increment Decrement Operators(++,--)
* Assignment operators (=,+=,-=,*=,/=,%=)
* Relational Operators (<,<=,>,>=,==,!=)
* Logical operators (&&,||,!)
* Bitwise operators (&,<<,>>,^,|,~)

**Arithmetic Operators**

* Addition (+)

Adds together two values.

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int val1=10;
    int val2=20;
    int sum=val1+val2;
    
    printf("%d",sum);
    
    return 0;
}
```
**⚙️ Output :**
>30

* Substraction (-)

Subtracts one value from another.

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int val1=10;
    int val2=20;
    int sum=val1-val2;
    
    printf("%d",sum);
    
    return 0;
}
```
**⚙️ Output :**
>-10

* Multiplication (*)

Multiplies two values.

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int val1=10;
    int val2=20;
    int sum=val1*val2;
    
    printf("%d",sum);
    
    return 0;
}
```
**⚙️ Output :**
>200

* Division (/)

Divides one value by another.

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int val1=30;
    int val2=20;
    int sum=val1/val2;
    
    printf("%d",sum);
    
    return 0;
}
```
**⚙️ Output :**
>1

* Modulus (%)

Returns the division remainder

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int result=11 % 4;
    
    printf("%d",result);
    
    return 0;
}
```
**⚙️ Output :**
>3

## Comments in C

Comments can be used to explain code, and to make it more readable. 

## Single-line Comments

Single-line comment are use to comment in single line.
Single-line comments start with two forward slashes (`//`).

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    // This is a comment
      printf("Hye!");
    
    return 0;
}
```
**⚙️ Output :**
>Hye!

## Multi-line Comments

Multi-line comment are used comment in multiple Line.
Multi-line comments start with `/*` and ends with `*/`.

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    /* This is a Multi-line comment
    and multi-line comment are use to comment on multiple line.*/

      printf("Hye!");
    
    return 0;
}
```
**⚙️ Output :**
>Hye!


## 🔗 Some Useful Links

## 📖 References
