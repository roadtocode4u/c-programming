# Lecture-11 Nested-If in C Programming 

## Nested-If

Nested If in C Programming is placing If Statement inside another IF Statement. Nested If in C is helpful if you want to check the condition inside a condtion. 

**Syntax :**
```c
if(condition 1)
{
   if(condition 2) {
      //Statement block Executes when the boolean test expression two is true.
   }
}
else
{
    //else statement block
}
```

**💻Example:**
```c

#include <stdio.h>

int main() {
    int hsc=80;
    int jee=130;
    
    if(hsc>=60)
    {
        printf("You cleared HSC");
        
        if(jee>=120)
        {
            printf("\nYou cleared JEE");
        }
        else
        {
            printf("\n You did not cleared JEE");
        }
    }
    else
    {
        printf("You did not cleared HSC");
    }
    
    return 0;
}
```
**⚙️ Output :**
>You cleared HSC   
You cleared JEE

**💻Example:**
```c
#include <stdio.h>

int main() {
    int a,b,c;
    printf("Enter the values of a,b,c");
    scanf("%d%d%d",&a,&b,&c);
    
    if(a>b)
    {
        if(a>c)
        {
            printf("%d is greatest",a);
        }
        else
        {
            printf("%d is greatest",c);
        }
    }
    else
    {
       if(b>c)
        {
            printf("%d is greatest",b);
        }
        else
        {
            printf("%d is greatest",c);
        }
    }
    
    return 0;
}
```
**⚙️ Output :**
>Enter the values of a,b,c 300 200 100   
300 200 100  
300 is greatest

**💻Example:**
```c

#include <stdio.h>

int main() {
    int a,b,c;
    printf("Enter the values of a,b,c");
    scanf("%d%d%d",&a,&b,&c);
    
    if(a>b && a>c)
    {
        printf("%d is greatest",a);
    }
    else if(b>a && b>c )
        {
            printf("%d is greatest",b);
        }
    
    else
        {
            printf("%d is greatest",c);
        }
    return 0;
}
```
**⚙️ Output :**
>Enter the values of a,b,c 20 10 30  
20 10 30   
30 is greatest

## 🔗 Some Useful Links

## 📖 References