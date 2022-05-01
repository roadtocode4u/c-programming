# Lecture-14 Break,Continue Keyword , While,Do-while loop in C Programming 

## Break  Keyword

Break keyword are used to stop loop permanently.

**💻Example:**

```c
//Break Keyword 

#include <stdio.h>

int main() {
    
    for(int i=1;i<=10;i++)
    {
        if(i==5)
        {
            break;
        }
        printf("\n%d",i);
    }
    
    return 0;
}
```
**⚙️ Output :** 
>1           
2         
3          
4          

## Continue Keyword

continue keyword are used to stop current loop.

**💻Example:**

```c
//continue Keyword 

#include <stdio.h>

int main() {
    
    for(int i=1;i<=10;i++)
    {
        if(i==5)
        {
            continue;
        }
        printf("\n%d",i);
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

## While Loop

* Entry Controlled
* Pre-Tested Loop
* if condition will false it will run zero times 

**Syntax:**
```c
while(condion)
{

}
```

**💻Example :**

```c
while(condition)
{
#include <stdio.h>

int main() {
    
    int i=0;
    
    while(i<5)
    {
        printf("\n%d",i);
        
        i++;
    }
    return 0;
}
```
**⚙️ Output :** 
0       
1       
2       
3    
4  

## Do-While Loop

* Exit Controlled
* Post-Tested Loop 
* if condition will false it will run ones

**Syntax:**
```c
do
{
 
}
while(condition);
```

**💻Example:**
```c
#include <stdio.h>

int main() {
    
    int i=0;
    
    do
    {
        printf("\n%d",i);
        
        i++;
    }
    
    while(i<5);
    
    return 0;
}
```
**⚙️ Output :** 
>0     
1     
2      
3    
4    


## 🔗 Some Useful Links

## 📖 References