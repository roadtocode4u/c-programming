# Lecture-14 Example Of Loop in C Programming 

**💻Example:**

```c
#include <stdio.h>

int main() {
    
    int i=1;
    
    while(i<=10)
    {
        if(i==5)
        {
            i++;
            continue;
        }
        printf("%d\n",i);
         i++;
    }
    
    return 0;
}
```
**⚙️ Output :** 
>1           
2       
3         
4         
6           
7           
8         
9      
10             


**💻Example:**

```c
#include <stdio.h>

int main() {
    
    int i=1;
    
    do
    {
         if(i==5)
         {
           break;
         }
         printf("\n%d",i);
         i++;
    }
    while(i<10);
    
    
    return 0;
}
```
**⚙️ Output :** 
>1       
2        
3       
4      
                   
**💻Example :**

```c
#include <stdio.h>

int main() {
    
    int i=1;
    
    do
    {
         if(i==5)
         {
             i++;
           continue;
         }
         printf("\n%d",i);
         i++;
    }
    while(i<10);
    
    
    return 0;
}
```
**⚙️ Output :** 
>0     
1     
2      
3    
4   
5    
6    
7    
8   
9

**💻Example :**

```c
#include <stdio.h>

int main() {
    
    for(int i=1;i<=5;i++)
    {
        int roll;
        printf("\nEnter Roll:");
        scanf("%d",&roll);
        printf("\n Your roll is:%d",roll);
    }
    return 0;
}
```
**⚙️ Output :** 
>Enter Roll:1    
Your roll is:1   
Enter Roll:2   
Your roll is:2 

**💻Example :**

```c
#include <stdio.h>

int main() { 
    char ch=1;
    
    while(ch==1)
    {
        printf("\nHello");
        printf("\n Do you want to Continue (1/0):");
        scanf("%d",&ch);
    }
    return 0;
}
```
**⚙️ Output :** 
>Hello     
 Do you want to Continue (1/0):1     
 Hello                          
 Do you want to Continue (1/0):1        
 Hello  
 Do you want to Continue (1/0):1     
 Hello        
 Do you want to Continue (1/0): 

 **Homework 🏠**
 > Write a C Program to reverse number using while loop 

## 🔗 Some Useful Links

## 📖 References