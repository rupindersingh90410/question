## What does the code results in?
```js
function printArray(a) 
{
     var len = a.length, i = 0;
     if (len == 0)
        console.log("Empty Array");
     else 
     {
         do 
         {
             console.log(a[i]);
         } while (++i < len);
     }
}

```
1. Prints the numbers in the array in order
2. Prints the numbers in the array in the reverse order
3. Prints 0 to the length of the array
4. Prints “Empty Array”

## Answer : A