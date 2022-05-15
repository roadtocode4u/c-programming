# Reverse an Array and Strings in C Programming 

## Array

Q1. Print an array in reverse format.


**💻Example 1 :**

```c
#include <stdio.h>

int main() {
    
    int arr[6] = {18, 2, 17, 19, 21, 45};
    
    for(int i=5; i>=0; i--)
    {
        printf("%d, ", arr[i]);
    }
    
    return 0;
}
```
**⚙️ Output :** 
>45, 21, 19, 17, 2, 18, 

**💻Example 2 :**
```c
#include <stdio.h>

int main() {
    
    int arr[6] = {18, 2, 17, 19, 21, 45};
    
      printf("\n Before Reverse: ");
    for(int i=0; i<6; i++)
    {
        printf("%d, ",arr[i]);
    }
    
    int start=0;
    int end=5;
    
    while(start<end)
    {
        int temp = arr[start];
        arr[start] = arr[end];
        arr[end] = temp;
        
        start++;
        end--;
    }
    printf("\n After Reverse: ");
    for(int i=0; i<6; i++)
    {
        printf("%d, ",arr[i]);
    }
    
    return 0;
}
```
**⚙️ Output :** 
>Before Reverse: 18, 2, 17, 19, 21, 45, <br>
After Reverse: 45, 21, 19, 17, 2, 18, 

<br>

## Strings

Strings are nothing but array or collection of characters.<br>
_Array of characters terminated by a null character '\0'._<br>

*Declaration of strings*

**💻Example 3 :**
```c
#include <stdio.h>

int main() {
    
    char name[] = "Suraj";
    
    printf("%s", name);
    
    return 0;
}
```
**⚙️ Output :** 
>Suraj

**💻Example 4 :**
```c
#include <stdio.h>

int main() {
    
    char name[50] = "Divyalaxmi";
    
    printf("%s", name);
    
    return 0;
}
```
**⚙️ Output :** 
>Divyalaxmi

<br>

**🏠Homework**
> 

## 🔗 Some Useful Links

## 📖 References