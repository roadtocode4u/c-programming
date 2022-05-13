# Lecture-23 Types of Functions Based on Arguments and Returntype in C Programming 

## Function argument and return values

**There are following categories:**<br>
* Function with arguments and return value.
* Function with arguments but no return value.
* Function with no arguments but returns a value.
* Function with no argument and no return value. <br>

_Function with arguments and return value_

**💻Example 1 :**
#### WAP to calculate area of rectangle
```c
#include <stdio.h>

int cal_area(int l, int b)
{
    int area = l * b;
    
    return area;
}
int main() {
    
    int l, b, area;
    
    printf("Enter length & breadth: ");
    scanf("%d%d",&l, &b);
    
    area = cal_area(l, b);
    
    printf("Area: %d",area);
    
    return 0;
}
```
**⚙️ Output :** 
>Enter length & breadth: 10 5<br>
Area: 50

<br>  

_Function with arguments but no return value._

**💻Example 2 :**
```c
#include <stdio.h>

void cal_area(int l, int b)
{
    int area = l * b;
    
    printf("Area: %d",area);
    
}
int main() {
    
    int l, b;
    
    printf("Enter length & breadth: ");
    scanf("%d%d",&l, &b);
    
    cal_area(l, b);
    
    return 0;
}
```
**⚙️ Output :** 
>Enter length & breadth: 10 5<br>
Area: 50

<br>

_Function with no arguments but returns a value._

**💻Example 3 :**
```c
#include <stdio.h>

int cal_area()
{
    int l, b;
    
    printf("Enter length & breadth: ");
    scanf("%d%d",&l, &b);
    
    int area = l * b;
    
    return area;
}

int main() {
    
    int area = cal_area();
    
    printf("Area: %d", area);
    
    return 0;
}
```
**⚙️ Output :** 
>Enter length & breadth: 10 5<br>
Area: 50

<br>

_Function with no argument and no return value._

**💻Example 4 :**
```c
#include <stdio.h>

void cal_area()
{
    int l, b;
    
    printf("Enter length & breadth: ");
    scanf("%d%d",&l, &b);
    
    int area = l * b;
    
    printf("Area: %d", area);
}

int main() {
    
    cal_area();
    
    return 0;
}
```
**⚙️ Output :** 
>Enter length & breadth: 10 5<br>
Area: 50

**🏠Homework**
>WAP to calculate simple interest using all 4 types of functions.
## 🔗 Some Useful Links

## 📖 References