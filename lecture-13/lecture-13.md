# Lecture-13 Practice Questions In  Loops in C Programming 

## Practice Question in Loops

**💻Example:**
```c
//Odd Numbers 

#include <stdio.h>

int main() {
    
    int n;
    printf("Enter Number :");
    scanf("%d",&n);
    
    for(int i=1;i<=n;i++)
    {
        if(i%2==1)
        {
            printf("\n%d",i);
        }
    }
    
    return 0;
}
```
**⚙️ Output :** 
>Enter Number :5   
1         
3         
5      

**💻Example:**
```c
// Even Numbers 
#include <stdio.h>

int main() {
    
    int n;
    printf("Enter Number :");
    scanf("%d",&n);
    
    for(int i=2;i<=n;i++)
    {
        if(i%2==0)
        {
            printf("\n%d",i);
        }
    }
    
    return 0;
}
```
**⚙️ Output :** 
>Enter Number :10          
2         
4           
6         
8        
10                   

**💻Example:**
```c
// Sum of  Numbers 
#include <stdio.h>

int main() {
    
    int n=3;
    
    printf("Enter Number :");
    scanf("%d",&n);
    
    int sum=0;
    
    for(int i=1;i<=n;i++)
    {
        sum=sum+i;
    }
    
    printf("Sum=%d",sum);
    
    return 0;
}
```
**⚙️ Output :**
>Enter Number :10    
Sum=55        

**💻Example:**
```c
// Factorial Of Numbers 
#include <stdio.h>

int main() {
    
    int n;
    printf("Enter Number :");
    scanf("%d",&n);
    
    int fact=1;
    
    for(int i=1;i<=n;i++)
    {
        fact=fact * i;
    }
    
    printf("Factorial=%d",fact);
    return 0;
}
```
**⚙️ Output :**
>Enter Number :5       
Factorial=120  

**💻Example:**
```c

#include <stdio.h>

int main() {
    
    int n;
    printf("Enter Number :");
    scanf("%d",&n);
    
    for(int i=1;i<=n;i++)
    {
        if(i%3==0 && i%5==0)
        {
            printf("\n%d is Divisible by both ",i);
        }
        else if (i%3==0 && i%5==0)
        {
            printf("\n%d is Divisible by 3 Or 5",i);
        }
        else
        {
            printf("\n%d is not Divisible by 3 Or 5",i);
        }
    }
    
    return 0;
}
```
**⚙️ Output :** 
>Enter Number :15           
1 is not Divisible by 3 Or 5             
2 is not Divisible by 3 Or 5   
3 is not Divisible by 3 Or 5     
4 is not Divisible by 3 Or 5          
5 is not Divisible by 3 Or 5          
6 is not Divisible by 3 Or 5           
7 is not Divisible by 3 Or 5      
8 is not Divisible by 3 Or 5      
9 is not Divisible by 3 Or 5         
10 is not Divisible by 3 Or 5         
11 is not Divisible by 3 Or 5           
12 is not Divisible by 3 Or 5          
13 is not Divisible by 3 Or 5          
14 is not Divisible by 3 Or 5           
15 is Divisible by both      

## 🔗 Some Useful Links

## 📖 References