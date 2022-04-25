# Lecture-10 If-Else Ladder in C Programming 

## If-Else Ladder

**Syntax :**
```c
if(condition1)
{
   //block of statement
}
else if(condition 2)
{
  //block of statement
}
else if(condition 3)
{
  //block of statement
}
else
{
  //block of statement  
}
```

**💻Example:**
```c
#include <stdio.h>

int main() {
  
   int marks = 95;
   
   if (marks>95)
   {
       printf("Grade A ");
   }
   else if(marks>80)
   {
       printf("Grade B");
   }
   else if(marks>70)
   {
       printf("Grade c");
   }
   else
   {
       printf("FAIl");
   }

    return 0;
}
```
**⚙️ Output :**
>Grade B

**💻Example:**
```c
#include <stdio.h>

int main() {
  
   int marks = 61;
   
   if (marks>60)
   {
       printf("Grade D");
   }
   else if(marks>70)
   {
       printf("Grade C");
   }
   else if(marks>80)
   {
       printf("Grade B");
   }
   else if(marks>90)
   {
       printf("Grade A");
   }
   else
   {
       printf("FAIl");
   }

    return 0;
}
```
**⚙️ Output :**
>Grade D

**💻Example:**
```c
#include <stdio.h>

int main() {
  
   int marks = 95;
   
   if (marks>90 && marks<=100)
   {
       printf("Grade A ");
   }
   else if(marks>80 && marks<=90)
   {
       printf("Grade B");
   }
   else if(marks>70 && marks<=80)
   {
       printf("Grade B");
   }
   else if (marks>60 && marks<=70)
   {
       prinf(" Grade D")
   }
   else
   {
       printf("FAIl");
   }

    return 0;
}
```
**⚙️ Output :**
>Grade A


## 🔗 Some Useful Links

## 📖 References